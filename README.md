<h1 align="left" style="margin-bottom: 20px; font-weight: 500; font-size: 50px; color: black;">
  FastAPI JWT Auth 2
</h1>

![Tests](https://github.com/alejorodriguez96/fastapi-jwt-auth/workflows/Tests/badge.svg)
[![Coverage Status](https://coveralls.io/repos/github/alejorodriguez96/fastapi-jwt-auth/badge.svg?branch=master)](https://coveralls.io/github/alejorodriguez96/fastapi-jwt-auth?branch=master)
[![PyPI version](https://badge.fury.io/py/fastapi-jwt-auth.svg)](https://badge.fury.io/py/fastapi-jwt-auth)
[![Downloads](https://static.pepy.tech/personalized-badge/fastapi-jwt-auth?period=total&units=international_system&left_color=grey&right_color=brightgreen&left_text=Downloads)](https://pepy.tech/project/fastapi-jwt-auth)

---

Proyect forked from [IndominusByte](https://github.com/IndominusByte)'s [fastapi-jwt-auth](https://github.com/IndominusByte/fastapi-jwt-auth). Since it seems to be no longer maintained (last commit was on Nov 11, 2020) I decide to fork the repo and add support for `pydantic==2.X`. If this isn't the appropiate way to fix the dependencies problem, please contact me so I can do it in the proper way. Thanks!

**Documentation**: <a href="https://alejorodriguez96.github.io/fastapi-jwt-auth" target="_blank">https://alejorodriguez96.github.io/fastapi-jwt-auth</a>

**Source Code**: <a href="https://github.com/alejorodriguez96/fastapi-jwt-auth" target="_blank">https://github.com/alejorodriguez96/fastapi-jwt-auth</a>

---

## Features
FastAPI extension that provides JWT Auth support (secure, easy to use and lightweight), if you were familiar with flask-jwt-extended this extension suitable for you, cause this extension inspired by flask-jwt-extended 😀

- Access tokens and refresh tokens
- Freshness Tokens
- Revoking Tokens
- Support for WebSocket authorization
- Support for adding custom claims to JSON Web Tokens
- Storing tokens in cookies and CSRF protection

## Installation
The easiest way to start working with this extension with pip

```bash
pip install fastapi-jwt-auth
```

If you want to use asymmetric (public/private) key signing algorithms, include the <b>asymmetric</b> extra requirements.
```bash
pip install 'fastapi-jwt-auth[asymmetric]'
```

## License
This project is licensed under the terms of the MIT license.
