# `@ubiquity-os/personal-agent`

The Personal Agent is a [UbiquityOS](https://github.com/apps/ubiquity-os) plugin designed to perform actions in the context of user's Github account. It is forked, configured, and hosted by a Github user. Any issue comment beginning with `/@username` is forwarded to user's personal-agent for processing. Find below a list features offered by the plugin:

- `/@username say hello`
  The plugin responds to such command with a `Hello`.

Communication between [UbiquityOS](https://github.com/apps/ubiquity-os) and the [Personal Agent plugin](https://github.com/EresDevOrg/personal-agent) is handled by [Personal Agent Bridge](https://github.com/EresDevOrg/personal-agent-bridge).

## Configuration

- Make sure the Personal Agent Bridge is also configured. You can read its [documentation](https://github.com/EresDevOrg/personal-agent-bridge/blob/plugin-pa-bridge/README.md).

- Fork this repository with exactly the same name `personal-agent` under your personal or your organization account.

- Generate a Github fine-grained Personal Access Token PAT with access to this repository only. Required permission: `Actions: read & write`, `Metadata: Read-only`

- Encrypt your PAT with UbiquityOS X25519_PUBLIC_KEY using [keygen.ubq.fi](https://keygen.ubq.fi/).

- Add the encrypted PAT in your fork's `.github/personal-agent.config.yml` file.

## Usage

Go to any repository issue where UbiquityOS is installed. Comment as below:

```
/@username say hello`
```

Do not forget to replace `username` with username where the plugin has been forked. You should get a reply from the personal-agent.

## Troubleshooting

In most cases you should also receive error message if there is a problem. If you do not get any response make sure to check the following:

- You are using the correct instance of UbiquityOS and it is running.
- Check Personal Agent Bridge and Personal Agent fork's actions logs.

### Get started with development

- Install dependencies

```
yarn install
```

- Run tests

```
yarn test
```

## More information

The initial discussion about the development of this plugin can be found [here](https://github.com/ubiquity-os/plugins-wishlist/issues/3).
