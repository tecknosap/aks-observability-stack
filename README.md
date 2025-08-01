# Project 6: Observability Stack on AKS with Fluent Bit, Prometheus, and Grafana

## Overview

This project models enterprise-grade observability practices by deploying a fully integrated logging and metrics stack on AKS, enabling real-time monitoring and alerting.

## Business Problem Solved

Lack of centralized logs and metrics limits operational visibility. Enterprises require scalable, secure observability platforms to maintain uptime and performance.

## What You Will Build

- Fluent Bit DaemonSet for Kubernetes log collection and forwarding.
- Prometheus Operator for Kubernetes metrics collection.
- Grafana dashboards secured with authentication.
- TLS encryption and RBAC for observability stack.

## Enterprise Impact

- Enhances operational awareness and troubleshooting speed.
- Supports SLAs through proactive monitoring.
- Complies with enterprise security requirements.

## Step-by-Step

1. Deploy Fluent Bit DaemonSet with Azure Monitor integration.
2. Install Prometheus Operator with resource monitoring configured.
3. Deploy Grafana with secured dashboards.
4. Enable TLS and Kubernetes RBAC for observability components.
5. Validate logs and metrics flow end-to-end.

## Prerequisites

- Running AKS cluster
- Kubernetes and Helm CLI installed

## References

- [Fluent Bit for Kubernetes](https://fluentbit.io/)
- [Prometheus Operator](https://github.com/prometheus-operator/prometheus-operator)
- [Grafana Authentication](https://grafana.com/docs/grafana/latest/auth/)
