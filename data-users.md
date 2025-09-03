---
title: How to Access ESGF Data
---

There are several ways to access ESGF data, depending on your needs and preferred workflow. Whether you want a user-friendly web interface, programmatic access for analysis, or tools to manage large-scale downloads, ESGF offers flexible options. Below is an overview of the main methods:

**Metagrid**
: MetaGrid is the next-generation search interface for the Earth System Grid Federation (ESGF). It's a user-friendly web application designed to help researchers find and access climate model data stored within the ESGF. Think of it as a more advanced way to search for and retrieve the data needed for climate research. For more information visit&nbsp;[Metagrid](./metagrid-guide.md)

**intake-esgf**
: `intake-esgf` is an [intake-esm](https://github.com/intake/intake-esm) _inspired_ package under development by ESGF2 that provides programmatic access to ESGF data holdings. The main difference is that in place of querying a static index, which is completely loaded at runtime, `intake-esgf` catalogs initialize empty and are populated by searching, querying ESGF index nodes dynamically. For more information visit&nbsp;[Intake-ESGF](./Intake-ESGF.md)

**Cookbooks**
: The ESGF Cookbook focuses on highlighting analysis recipes, as well as data acccess methods, all accesible within the Python programming language. This cookbook also spans beyond the scope of a single Climate Model Intercomparison Project (ex. CMIP6), expanding to other experiments/datasets such as CMIP5 and obs4MIPs. For more information visit&nbsp;[Cookbooks](./Cookbooks.md)

**ESG Pull**
: esgpull is a modern ESGF data management tool, bundled with a custom asynchronous interface with the ESGF Search API. It handles scanning, downloading and updating datasets, files and queries from ESGF. For more information visit&nbsp;[ESG Pull](./ESG-Pull.md)
