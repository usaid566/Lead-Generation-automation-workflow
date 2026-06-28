**# Lead-Generation-automation-workflow**# Lead Generator Workflow Overview

## Overview

This workflow automatically generates up to five sample B2B leads using predefined company and decision-maker details. The leads are returned in a structured JSON format and stored directly in a Google Sheet. It is primarily intended for testing, demonstrations, and lead generation simulations.

## Purpose

This workflow enables you to:

* Generate realistic sample B2B leads for testing and demo environments.
* Automate lead creation using an AI model.
* Store generated leads in Google Sheets for easy access, review, and further processing.

## Workflow

1. A Manual Trigger starts the workflow.
2. Existing records are retrieved from a Google Sheet.
3. The required data is prepared and sent to the AI model.
4. The AI generates up to five fake leads in JSON format.
5. A JavaScript node parses and validates the AI response.
6. The generated leads are appended to or updated in the connected Google Sheet.

## Requirements

* An n8n instance
* Google Sheets OAuth credentials
* Google Gemini API credentials
* Access to the target Google Sheet

## How to Use

1. Import or open the workflow in n8n.
2. Connect your Google Sheets and Gemini credentials.
3. Execute the workflow using the **Execute Workflow** button.
4. Verify that the generated leads have been added to the connected Google Sheet.

## Notes

* All generated leads are fictional and intended solely for testing and demonstration purposes.
* The workflow expects the target Google Sheet to have the required column structure.
* The AI response must be valid JSON to ensure successful parsing and storage.
