# FileFlow

**Document tools delivered through WhatsApp, backed by a reusable application platform.**

## The problem

Someone already sent the document on WhatsApp. Making them download it, find a separate tool, process it, and upload it again adds a surprisingly long detour to a small task.

FileFlow brings supported document operations into that conversation, with dashboard controls and the processing infrastructure behind it.

## The solution

A document-tools industry/client implementation within the reusable single-tenant WhatsApp platform, rather than a separate chatbot built from scratch.

## What it does

- WhatsApp document intake and processing workflows.
- Configurable supported document operations.
- Shared inbox, authentication, AI, and dashboard infrastructure.
- Industry and client configuration with feature controls.
- Container packaging for native document-processing tools.
- A client-export delivery model that includes the required shared runtime.

## Engineering highlights

Integrates document operations with message intake, temporary-file handling, storage, dashboard controls, and native-tool container packaging. The client-export model delivers the complete shared runtime together with the selected document-tools configuration.

## Technology

Next.js, TypeScript, the WhatsApp platform, Supabase/Postgres, Docker, qpdf, pdfcpu, Poppler, LibreOffice.

## Source code

This repository documents the project, its capabilities, and the engineering behind it. The application source code is maintained privately.
