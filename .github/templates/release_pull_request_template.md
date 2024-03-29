- [x] Branch: Starting from `master`, create a release branch named `release/X.Y.Z` for your changes.
- [ ] Version bump: Update the version number in `plugin-main-file.php`, `package.json` and stable tag in `readme.txt` to `X.Y.Z` (e.g. 1.2.3).
- [ ] Tested up to WP: Update the `Tested up to` version in `readme.txt` to the latest version of WordPress.
- [ ] Tested up to WC: Update the `WC tested up to` version in `plugin-main-file.php` to the latest version of WooCommerce.
- [ ] Changelog: Add a new entry to the `readme.txt` file under the `== Changelog ==` section or `changelog.txt` file.
- [ ] Build: Run `./bin/build.sh` to build the plugin.
- [ ] Test: Test the plugin to ensure that it works as expected.
- [ ] Commit: Commit the changes and push the release branch to the repository.
- [ ] Pull Request: Create a pull request from the release branch to `master`.
- [ ] Release: Once the pull request is merged, create a new release. Set the tag version to `X.Y.Z` and the release title to `X.Y.Z`. Copy the changelog entry to the release description and publish the release.
- [ ] ZIP: Download the release ZIP file from GitHub and upload it to the related locations.
- [ ] Demo: If applicable, update the demo site with the new version.
- [ ] Announce: Announce the new release on the appropriate channels with the changelog entry and a link to the release.
