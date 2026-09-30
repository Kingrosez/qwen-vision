# Copilot Model Restoration Instructions

This repository contains an Ollama model package
split into numbered binary parts.

## Repository information

- Repository: Kingrosez/qwen-vision
- Branch: main
- Metadata: model-metadata.json
- Manifest: chunk-manifest.json
- Chunk directory: parts/

## Required workflow

1. Inspect model-metadata.json and chunk-manifest.json.
2. Confirm the repository, model, package name, chunk count,
   and expected package SHA-256.
3. Check the applicable organizational and VDI policies
   before accessing or downloading repository content.
4. Obtain all numbered chunk files listed by the manifest.
5. Verify each chunk against its manifest SHA-256 before
   using it.
6. Confirm the chunks are complete and ordered numerically.
7. Reconstruct the package only in an approved location
   using an approved process.
8. Verify the reconstructed package SHA-256 against
   model-metadata.json before proceeding.
9. Review the package contents and applicable license.
10. Ask the user to confirm the authorized Ollama import
    procedure for their environment before performing it.

## Safety and access constraints

- Do not request, display, or embed GitHub tokens,
  passwords, or other credentials.
- Do not assume that GitHub access or external downloads
  are permitted from the VDI.
- If access is blocked or policy is unclear, stop and
  ask the user for an approved workflow.
- Do not execute untrusted files or scripts from the
  repository.
- Do not claim restoration or import succeeded unless
  the authorized process confirms it.

OMM only packages and uploads model artifacts.
Restoration and Ollama import are handled separately
by the user's authorized VDI Copilot workflow.
