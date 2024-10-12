# mapping-puzzle-block

Custom block to add the mapping puzzle as an iframe embed to Wordpress websites.

## Development

1. Install depenedencies with `pnpm install`.
1. Start Docker.
1. Run `pnpm wp-env start` to start the WordPress environment.
1. Run `pnpm start` to watch for changes in `src`.
1. Open to <http://localhost:8888/wp-admin/> to log into the development server. Use `admin` and `password` as the credentials.
1. Install the "Create Block Theme" plugin under the **Plugins** menu. Active the plugin.
1. Under the **Appearance** menu, click **Manage Theme Fonts**. Add Lora (with weights 400 and 700) and Open Sans (with weights 400 and 700) from Google Fonts.

Stop the WordPress environment with `pnpm wp-env stop`. Delete the WordPress environment with `pnpm wp-env destroy`.

Run `pnpm wp-env --help` to see all available commands.

## Installation

Run `pnpm zip` to create a ZIP file of the block plugin.