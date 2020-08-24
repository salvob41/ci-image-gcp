# Google cloud sdk with kubectl

Docker image with Google Cloud SDK and Kubectl. For use with [CI templates](https://github.com/jobtome-labs/ci-templates/).

It also includes [kube-score](https://github.com/zegl/kube-score) not built from source.

### Versions
|||
|-|-|
| cloud sdk | 299.0.0-alpine |
| kube-score | 1.2.1 |

To override these default versions:

`docker build -t linuxbandit/pythonlinter-reviewdog --build-arg CLOUD_SDK_VERSION=v9000 --build-arg KUBE_SCORE_VERSION=v1000 .`
