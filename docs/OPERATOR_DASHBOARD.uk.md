# Synera Operator Cockpit

## Overview

The Synera Operator Cockpit is an offline CNRA pilot operator cockpit that reads events from a JSON file, computes 5 panels and alerts, and emits static HTML and CSV. The cockpit provides real-time updates on operator health, cohort quality, operator load, revenue signals, and export capabilities.

## Installation

To install the Synera Operator Cockpit, you need to have Node.js and npm installed on your system. Then, run the following command in your terminal:

```bash
npm install synera-telemetry-v1
```

## Usage

1. **Run the Cockpit**: Execute the following command in your terminal:

   ```bash
   node operator_dashboard.mjs <events.jsonl> [output.html]
   ```

   Replace `<events.jsonl>` with the path to your events file and `[output.html]` with the desired output file name.

2. **CLI Entry**: If you run the script from the command line, you can specify the input and output paths using the following command:

   ```bash
   new URL('C:\...') parses the drive letter as a scheme, so the guard never matched and the
   CLI silently did nothing while exiting 0. pathToFileURL is the pattern neon/generate-schema.mjs uses.
   ```

   This will read the events from the specified JSON file, compute the necessary metrics, and write the results to the specified output file.

## Documentation

### 1. Installation

To install the Synera Operator Cockpit, you need to have Node.js and npm installed on your system. Then, run the following command in your terminal:

```bash
npm install synera-telemetry-v1
```

### 2. Usage

1. **Run the Cockpit**: Execute the following command in your terminal:

   ```bash
   node operator_dashboard.mjs <events.jsonl> [output.html]
   ```

   Replace `<events.jsonl>` with the path to your events file and `[output.html]` with the desired output file name.

2. **CLI Entry**: If you run the script from the command line, you can specify the input and output paths using the following command:

   ```bash
   new URL('C:\...') parses the drive letter as a scheme, so the guard never matched and the
   CLI silently did nothing while exiting 0. pathToFileURL is the pattern neon/generate-schema.mjs uses.
   ```

   This will read the events from the specified JSON file, compute the necessary metrics, and write the results to the specified output file.

### 3. Documentation

The Synera Operator Cockpit provides real-time updates on operator health, cohort quality, operator load, revenue signals, and export capabilities. The cockpit provides detailed information about each metric, including its status, duration, and any associated alerts.

## Conclusion

The Synera Operator Cockpit is an offline CNRA pilot operator cockpit that reads events from a JSON file, computes 5 panels and alerts, and emits static HTML and CSV. The cockpit provides real-time updates on operator health, cohort quality, operator load, revenue signals, and export capabilities. The cockpit provides detailed information about each metric, including its status, duration, and any associated alerts.