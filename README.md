Lead Generator Workflow
Overview

This workflow automatically generates up to five fake leads based on predefined company and decision-maker fields. The generated leads are structured in JSON format and saved directly to a Google Sheet. It is designed to support testing, demos, and lead-generation simulations.

Purpose

The workflow helps:

Generate sample B2B leads for testing and demonstrations

Automate structured lead creation using an AI model

Store generated leads in Google Sheets for easy access and review

Workflow Summary

A manual trigger starts the workflow.

Existing rows are fetched from a Google Sheet.

Data is prepared and passed to an AI model.

The AI model generates up to five fake leads in JSON format.

A JavaScript node parses the AI response.

The generated leads are appended to or updated in the Google Sheet.
Requirements

n8n instance

Google Sheets OAuth credentials

Google Gemini (PaLM) API credentials

Access to the target Google Sheet

How to Use

Open the workflow in n8n.

Ensure Google Sheets and Gemini credentials are connected.

Click Execute workflow.

Review the newly generated leads in the connected Google Sheet.

Notes

All generated data is fake and intended for testing only.

The workflow assumes the Google Sheet schema already exists.

Ensure the AI response remains valid JSON to avoid parsing errors.
