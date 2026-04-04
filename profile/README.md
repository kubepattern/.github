# KubePattern

> [!IMPORTANT]
> KubePattern is a Kubernetes smells detection engine written in Go, that helps you identify and fix anti-patterns in your Kubernetes cluster.
> It is useful to **identify Custom Resources that deviate from architectural principles** and to suggest the correct pattern to apply as a remedy.


## ✨ Overview

KubePattern is an innovative project that helps you identify configuration issues, anti-patterns, and improvement opportunities in your Kubernetes clusters. It combines static and dynamic analysis techniques to provide actionable insights and recommendations.

## 📋 How It Works
KubePattern helps you identify "smells" (anti-patterns or design flaws) in your cluster, which are defined in the pattern-as-code file. It then suggests you apply the correct pattern to resolve them.

1. **Scan**: KubePattern analyzes your cluster configuration
2. **Detect**: Identifies smells based on the defined patterns
3. **Suggest**: Recommends appropriate patterns based on best practices

> [!NOTE]
> Unlike traditional linters that only verify field presence, KubePattern identifies complex patterns and relationships between resources, providing contextual suggestions with reference documentation.

## Pattern as Code
Pattern-as-Code (PaC) is a Kubernetes Custom Resource Definition (CRD) that allows you to define metrics and patterns to recognize Kubernetes resources that deviate from architectural principles and best practices. They also are comprehensive of a remediation reverence documentation and a severity level to prioritize the most critical issues.

## Comprehensive Reporting
KubePattern generates detailed reports of detected smells, including severity levels, affected resources, and actionable recommendations. These reports are stored as Kubernetes Custom Resources (Smells), allowing you to query and manage them using standard Kubernetes tools.

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).
