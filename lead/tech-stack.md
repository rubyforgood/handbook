# Tech Stack

Since one of the main tenants of Ruby for Good is to have maintainable projects that will be used and evolved for years we strive to have a foundational tech stack.

This tech stack is not set in stone, we should be flexible and work with the stakeholders to make sure we are solving their problem in a way that works for them, using tools that make sense for their organization.

Likewise, these tools will evolve over time. This is a fluid list that will be updated as new versions of frameworks, libraries and other tools become available.

Main Tech Stack:

Most Recent version of Ruby on Rails. Typically with the following

| Feature      | Tool/Library                    | Notes                                                                                                                                 |
| ------------ | ------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| Language     | Ruby                            |                                                                                                                                       |
| Web Backend  | Ruby on Rails                   | The latest major version for greenfield projects                                                                                      |
| Web Frontend | Static HTML with minimal jQuery | More sophisticated frontend frameworks can be used where needed, but want to make sure we have a good reason                          |
| Testing      | RSpec or MiniTest               | Favor RSpec since it is a "batteries included" library without the need to pull in extra gems for mocking, stubbing and spies |
| Deployment   | Heroku or Digital Ocean         | If possible we should deploy to any existing infrastructure the organization already maintains                                        |

