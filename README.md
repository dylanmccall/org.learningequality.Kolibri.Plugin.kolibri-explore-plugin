# Flatpak extension for Kolibri Explore Plugin

This package is an extension for the [Kolibri flatpak](https://flathub.org/apps/details/org.learningequality.Kolibri) which provides [kolibri-explore-plugin](https://github.com/endlessm/kolibri-explore-plugin).

## Building

To build and install this package on your system, you will first need to have `org.learningequality.Kolibri` installed. Next, use flatpak-builder:

    flatpak-builder build-dir org.learningequality.Kolibri.Plugin.kolibri-explore-plugin.yaml --install --user

Once it is installed, you can enable the plugin in Kolibri:

    flatpak run --command=kolibri org.learningequality.Kolibri plugin enable kolibri_explore_plugin
