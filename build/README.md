# Phalcon Build

Docker images to build Phalcon in supported platforms.

## Supported Operating Systems

### Ubuntu

| Codename  | OS Release | Phalcon Releases  | PHP version  | Docker image                                        |
| --------- | ---------- | ----------------- | ------------ | --------------------------------------------------- |
| `trusty`  | 14.04 LTS  | `3.0.0` - `3.0.1` | `5.5.x`      | [`phalconphp/build:ubuntu-trusty`][:ubuntu-trusty:] |
| `wily`    | 15.10      | `3.0.0` - `3.0.1` | `5.6.x`      | [`phalconphp/build:ubuntu-wily`][:ubuntu-wily:]     |
| `xenial`  | 16.04 LTS  | `3.0.0` - `3.0.1` | `7.0.x`      | [`phalconphp/build:ubuntu-xenial`][:ubuntu-xenial:] |


### Debian

| Codename  | OS Release | Phalcon Releases  | PHP version  | Docker image                                        |
| --------- | ---------- | ----------------- | ------------ | --------------------------------------------------- |
| `jessie`  | 8.5 LTS    | `3.0.0` - `3.0.1` | `5.6.x`      | [`phalconphp/build:debian-jessie`][:debian-jessie:] |

[:ubuntu-trusty:]: https://github.com/phalcon/dockerfiles/blob/master/build/ubuntu-trusty/Dockerfile
[:ubuntu-wily:]: https://github.com/phalcon/dockerfiles/blob/master/build/ubuntu-wily/Dockerfile
[:ubuntu-xenial:]: https://github.com/phalcon/dockerfiles/blob/master/build/ubuntu-xenial/Dockerfile
[:debian-jessie:]: https://github.com/phalcon/dockerfiles/blob/master/build/debian-jessie/Dockerfile