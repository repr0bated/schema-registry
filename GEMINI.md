# Schema Registry Gemini Context

## Focus Area
**Versioning**

## Why Index?
Patterns for managing schema evolution and compatibility in your `Event Chain`.

## Project Description
Confluent Schema Registry provides a serving layer for your metadata. It stores a versioned history of schemas (Avro, JSON Schema, Protobuf).

## Key Concepts
- **Subjects**: Scope under which schemas are registered.
- **Compatibility**: Rules for schema evolution (Forward, Backward, Full).
- **Serializers**: Plugs into Kafka clients.

## Conventions
- **Language**: Java
- **Interface**: REST API.
