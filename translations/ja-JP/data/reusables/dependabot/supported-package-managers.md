| パッケージマネージャー                      | Supports vendoring |
| -------------------------------- |:------------------:|
| Bundler: `bundler`               |       **X**        |
| Cargo: `cargo`                   |                    |
| Composer: `composer`             |                    |
| Docker: `docker`                 |                    |
| Elm: `elm`                       |                    |
| gitサブモジュール:`gitsubmodule`        |                    |
| GitHub Actions: `github-actions` |                    |
| Goモジュール:`gomod`                  |       **X**        |
| Gradle: `gradle`                 |                    |
| Maven: `maven`                   |                    |
| Mix: `mix`                       |                    |
| npm: `npm`                       |                    |
| NuGet: `nuget`                   |                    |
| pip: `pip`                       |                    |
| Terraform: `terraform`           |                    |

{% note %}

**Note**: {% data variables.product.prodname_dependabot %} also supports the following package managers:

-`yarn` (v1 only) (specify `npm`)

-`pipenv`, `pip-compile`, and `poetry` (specify `pip`)

For example, if you use `poetry` to manage your Python dependencies and want {% data variables.product.prodname_dependabot %} to monitor your dependency manifest file for new versions, use `package-ecosystem: "pip"` in your *dependabot.yml* file.

{% endnote %}
