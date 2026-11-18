# Tilda T123

Paste T123-code.html into a T123 block on a separate, blank Tilda page, then publish. Disable shared header/footer for that page. The loader resets the T123 record top and bottom spacing.

All images, masks and fonts load from this public GitHub Pages directory. The original GitHub home page is unchanged. The layout lives in a Shadow DOM to avoid Tilda style conflicts. Native page scrolling, anchor navigation, photo lightbox, Yandex Maps and the swallow animation are preserved.

Rebuild from the current index.html with: node work/build-tilda-package.cjs
Publish the generated tilda/ tree together as one commit.
