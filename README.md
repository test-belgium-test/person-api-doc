
# Person API

This repository contains:

- Swagger API description for operations (POST, PUT, PATCH) on a Person entity.
- JSON Schema defining attributes of a Person including a Belgian SSIN.
- Jekyll static site configured with Swagger UI for documentation.

## How to use

- The Swagger API specification is located at `api-specification.yaml`.
- The JSON Schema for the Person entity is at `schemas/person-schema.json`.
- Documentation available at `docs/PERSON_API.md`.

## Jekyll site

Navigate to the `site` directory, then:

```
gem install bundler jekyll
bundle install
bundle exec jekyll serve
```

Swagger UI will be available at [http://localhost:4000/swagger-ui](http://localhost:4000/swagger-ui)
