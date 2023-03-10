#  Client Template

> NOTE: This project is just experiment. It should not be used by general public 

Generate various clients using OpenAPI generator.

## Contents

Project contains:

- Github actions automation for OpenAPI processing and generation
- OpenAPI processing tool for transforming OpenAPI schema
- OpenAPI generator setup with various scripts helping with generation

See [tools](./tools) for more info.

## How to use

1. Use this template to create new repository.
2. It will autocreate PRs with openapi and client updates using github actions.
3. Pick one of the availabe generators from OpenAPI generator:
https://openapi-generator.tech/docs/generators/

5. Edit tools/config/config.yaml file specifying generator name. Consider adding generator propoperties.
Example: 
https://github.com/wtrocki/api-client-template/blob/main/tools/config/config.yaml

## Why transformer?
OpenAPI file can be simplified in order to generate user-friendly code. Transformer can be used to modify openapi file to meet some needs of specific generator.
