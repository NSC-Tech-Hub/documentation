# The Vetting Loop Protocol

The Vetting Loop is the mandatory quality assurance process that all project assets and logic must pass through.

## 🔄 The Three-Stage Process

### Stage 1: Submission
* Department Liaisons submit assets/requirements to the "Incoming" pipeline.
* **Guardrail:** The TPM checks for compliance with `DESIGN_SPECS.md`.

### Stage 2: Technical Validation
* Assets are reviewed for performance impact and technical feasibility.
* Requirements are translated into **GitHub Issues** within the `projects` repository.

### Stage 3: Production Merge
* Once validated, the TPM moves the asset into the "Approved" folder.
* Developers are notified that the task is ready for implementation.

## 🚫 Rejection & Revision
If an asset fails validation (wrong format, missing info, unclear spec), it is returned to the Department Liaison with a "Reason for Revision" note. Work does not reach the Development team until Stage 3 is cleared.