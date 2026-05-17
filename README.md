# DiaCare AI

Phase-based monorepo for a diabetes Clinical Decision Support System (CDSS).

## Phase 1 scope

- Java 21 Spring Boot backend scaffold
- HL7 FHIR R4 Observation ingestion endpoint
- LOINC 15074-8 glucose validation
- Redis-backed CGM time-series storage
- PostgreSQL and Redis Docker runtime

## Run

```bash
docker compose up --build
```

The backend will start on `http://localhost:8080`.

#Diabetes Monitor System
