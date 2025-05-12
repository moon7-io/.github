# Moon7 Organization Configuration

This repository contains organization-wide GitHub configurations, templates, and community health files for all Moon7 projects.

## What's Included

- **Organization Profile**: The `profile/README.md` file that appears on the [Moon7 organization page](https://github.com/moon7-io)
- **Issue Templates**: Standard templates for bug reports, feature requests, and other issue types
- **Pull Request Template**: Standard template for all pull requests
- **GitHub Workflows**: Reusable CI/CD workflows for Moon7 projects
- **Community Health Files**: Organization-wide contributing guidelines, code of conduct, security policy, etc.

## Usage

These configuration files automatically apply to all repositories in the Moon7 organization that don't have their own versions of these files.

### Workflows

To use shared workflows in a repository, reference them with:

```yaml
uses: moon7-io/.github/.github/workflows/workflow-name.yml@main
```

## Contributing

Contributions to Moon7 projects are welcome. Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for more information on:

- Development workflow
- Testing and linting requirements
- Pull request process
- Commit guidelines

## License

All Moon7 libraries are released under the [MIT License](LICENSE) unless otherwise specified. See the LICENSE file in each repository for details.

## Acknowledgements

Moon7 is created and maintained by [Munir Hussin](https://github.com/profound7).

<a href="https://github.com/profound7"><img src="https://github.com/profound7.png?size=32" width="32" height="32" style="border-radius:50%;" alt="Munir Hussin"></a>