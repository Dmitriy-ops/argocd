<<<<<<< HEAD
# argocd
=======
# Helm Chart for vizitka-chart

## Introduction

This Helm chart deploys a web application (`dmitriyops/my_newsite`) with configurable settings for `dev` and `prod` environments.

## Installation

### For `dev` environment:

```bash
helm install my-release-dev ./vizitka-chart -f values-dev.yaml --namespace dev --create-namespace
>>>>>>> cc67cf5 (Initial commit for vizitka-chart)
