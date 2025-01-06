# SQL Query Visualization Tool

This tool transforms natural language queries into data visualizations, enabling users to interactively explore datasets. Users can upload SQLite databases or CSV files, ask questions in plain language, and receive relevant visualizations generated from SQL queries.

## Features
- Upload SQLite/CSV files (under 1MB)
- Ask questions in natural language
- Converts questions to SQL, executes them, and generates visualizations
- Visualizations in various formats (e.g., bar, scatter, pie)
- Uses LangGraph for query orchestration

## Demo
[Demo Video](demo.mov)

## System Overview

- SQLite server for file uploads and database management
- LangGraph orchestration for generating and executing SQL queries
- Frontend with visualization templates
- Integration with LangGraph’s streaming API

