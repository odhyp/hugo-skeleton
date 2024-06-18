{{- $removeDate := substr .Name 11 -}}
{{- $pageTitle := replace $removeDate "-" " " | title -}}
{{- $pageSlug := $removeDate -}}

+++
draft = true

title = '{{ $pageTitle }}'
date = {{ .Date }}
author = '{{ .Site.Params.author }}'
slug = '{{ $pageSlug }}'

tags = ['tag1', 'tag2', 'tag3']
summary = ''

project_url = ''
source_code = ''
+++

## Project Overview

<!-- Provide an overview of the project -->

## Features

<!-- List and describe the features of the project -->

## Installation

<!-- Provide instructions on how to install and use the project -->

## Usage

<!-- Provide usage examples and instructions -->

## Contributing

<!-- Explain how others can contribute to the project -->

## License

<!-- Include licensing information -->
