# CBGX Specification (`cbgx-spec`)

Welcome to the official specification repository for **CBGX** (**Comic Book Guided eXperience**).

CBGX is an open, platform-neutral container format (`.cbgx`) based on ZIP and JSON. It designed for digital comics, offering built-in metadata, normalized panel boundaries, and explicit reading orders for Guided View experiences.

## Repository Structure

- `specification/`: Formal specification documents for CBGX.
- `schemas/`: JSON Schema definitions (Draft 2020-12) used to validate `manifest.json`.
- `examples/`: Reference examples of valid and invalid `.cbgx` structures.
- `test-data/`: Shared test suites for SDK implementers.
- `media-type/`: Drafts for IANA MIME type registration (`application/vnd.cbgx+zip`).

## License

This specification is licensed under the [MIT License](LICENSE).
