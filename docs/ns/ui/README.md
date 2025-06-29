# Cadano UI XML Namespace

This repository contains the XML namespace definition and schema for the Cadano Operating System's user interface components.

## What is Cadano UI Namespace?

The Cadano UI namespace (`cadano:`) provides a structured way to define, style, and manage UI elements in XML format, tailored specifically for the Cadano OS ecosystem.

## Contents

- **index.html** — Documentation listing all `cadano:` attributes and their purposes.  
- **schema.json** — JSON Schema file describing valid attributes and their types, used for validating XML files and supporting IDE features.

## Usage

1. Reference the namespace in your XML UI files:

```xml
<view xmlns:cadano="https://yourusername.github.io/cadano-xmlns/ns/ui">
  <button cadano:id="btnSubmit" cadano:style="primary">Submit</button>
</view>