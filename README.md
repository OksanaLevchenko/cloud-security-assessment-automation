# Cloud Security Assessment Automation

This project automates security and compliance checks across container and Kubernetes environments. It brings together Trivy, Polaris, and Kubescape and uses Python to help collect and organize assessment results into a repeatable workflow.

## What it does

* runs security and configuration checks with established scanning tools
* collects scan output into a consistent workflow
* reduces repetitive manual assessment work
* supports repeatable security reviews across environments

## Tools

* Python
* Trivy
* Polaris
* Kubescape

## Why I built it

Security reviews often involve the same sequence of checks, result collection, and report preparation. I wanted to reduce the manual part of that process and make the assessment workflow easier to repeat.

## Project files

The main automation logic is implemented in Python scripts in this repository, including report generation and supporting utilities.

## Running the project

Install the required Python dependencies:

```bash
pip install -r requirements.txt
```

Run the assessment automation from the repository using the project scripts and configuration available in the codebase.

## What this demonstrates

This project is mainly about DevSecOps automation rather than building a scanner from scratch. The value is in orchestrating existing security tools, handling their output, and making the process easier to run consistently.

## Next improvements

I would extend the project with CI integration, normalized JSON output, severity thresholds, artifact publishing, and policy based pass or fail conditions for pull requests and deployment pipelines.
