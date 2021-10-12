# Format for Open Interactive Math Exercises

The goal of this repository to facilitate the development of an open format for online, interactive math exercises.
The first version of the format is defined using the [JSON Schema vocabulary](http://json-schema.org/) and is captured in the following schemas:

- [exercises.schema.json](./exercise.schema.json): the main schema for different type of exercises, you probably want to start here.
- [parameter.schema.json](./parameter.schema.json): a schema to define different types of parameters
- [content-types.schema.json](./content-types.schema.json): common definitions of types used in the other two schemas. 

#### Note: the current version of the format is `v0.0.1` and is published to sollicit feedback from the community. Please keep in mind that this format can (and most likely will) change in the future.

## Providing feedback
If you have any feedback please feel free to create a pull request with proposed changes, create an issue with your feedback, or comment on [this commit](https://github.com/grasple/open-format-schemas/commit/76b6177c8d74227e33e79442d70ee7044016d9c8).
