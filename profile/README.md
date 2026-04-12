# KubePattern
## ✨ Overview

KubePattern is a cloud-native framework, written in Go, designed to analyze Kubernetes Resources Interactions and spot violations.
It is useful to identify Custom Resources that deviate from architectural principles and to suggest the correct pattern to apply as a remedy.

## 📋 How It Works
KubePattern helps you identify "smells" (anti-patterns or design flaws) in your cluster defined by the applied Patterns.

### The Process
1. Define Patterns: You define architectural patterns as Kubernetes Custom Resources (Patterns) in your cluster
2. Apply Patterns: You apply these patterns to your cluster.
3. Retrieve Patterns: KubePattern retrieves the defined patterns from the cluster
4. Retrieve Resources: KubePattern analyzes your cluster configuration
5. Detect: Identifies targets resources based on the defined patterns
6. Warn: Generates reports with severity levels and actionable recommendations
7. Remediate: Once a smell is resolved, Smells are automatically removed from the cluster

> [!NOTE]
> Unlike traditional linters that only verify field presence, KubePattern identifies complex patterns and relationships between resources, providing contextual suggestions with reference documentation.

## 📄 License

This project is licensed under the [Apache License 2.0](LICENSE).
