# AI Application Specification Language (AIASL)

AIASL is a YAML-based specification language for defining applications to be built by AI systems. It provides a structured way to describe application architecture, infrastructure, components, and deployment requirements.

## Directory Structure

```
.
├── LICENSE
├── README.md
└── examples/
    ├── simple/
    │   ├── landing-page.yaml
    │   └── static-site.yaml
    ├── frontend-backend/
    │   ├── react-express.yaml
    │   ├── vue-fastapi.yaml
    │   ├── vite-laravel.yaml
    |   └── angular-springboot.yaml
    ├── microservices/
    │   └── all-services.yaml
    ├── fullstack/
    │   ├── laravel.yaml
    │   ├── wordpress.yaml
    │   └── rails.yaml
    └── nextjs/
        └── next-js.yaml
```

## Quick Start

1. Choose an example that matches your needs
2. Copy the YAML file
3. Modify according to your requirements
4. Use with your AI toolchain

If necessary setup your AI model with the language definition file to generate the code. [Language Definition File](ai-prompt-lang-def.md)

## Example Usage

```yaml
version: "1.0"
metadata:
  title: "My Application"
architecture:
  type: "fullstack"
  pattern: "mvc"
```

## Specification Sections

- Metadata
- Architecture
- Infrastructure
- Components
- Data Model
- Security
- Performance
- Deployment

Read the manual for detailed information on each section. [Read Manual](manual.md)

## Use Cases

- Defining application structure for AI-assisted development
- Documenting application architecture
- Standardizing project specifications
- Generating boilerplate code

## Contributing

1. Fork the repository
2. Create a new branch (`git checkout -b feature`)
3. Make changes
4. Commit your changes (`git commit -am 'Add feature'`)
5. Push to the branch (`git push origin feature`)
6. Create a new Pull Request


## License

MIT License

Copyright (c) 2024

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.