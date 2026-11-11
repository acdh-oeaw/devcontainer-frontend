FROM node:26-trixie-slim

LABEL org.opencontainers.image.description="ACDH frontend devcontainer"

ENV DEBIAN_FRONTEND=noninteractive

RUN npm install --global pnpm@12

# playwright dependencies
# @see playwright install --dry-run --with-deps
RUN \
  apt-get update \
  && apt-get install --no-install-recommends -y \
    libasound2t64 \
    libatk-bridge2.0-0t64 \
    libatk1.0-0t64 \
    libatspi2.0-0t64 \
    libcairo2 \
    libcups2t64 \
    libdbus-1-3 \
    libdrm2 \
    libgbm1 \
    libglib2.0-0t64 \
    libnspr4 \
    libnss3 \
    libpango-1.0-0 \
    libx11-6 \
    libxcb1 \
    libxcomposite1 \
    libxdamage1 \
    libxext6 \
    libxfixes3 \
    libxkbcommon0 \
    libxrandr2 \
    libavcodec61 \
    libcairo-gobject2 \
    libdbus-glib-1-2 \
    libfontconfig1 \
    libfreetype6 \
    libgdk-pixbuf-2.0-0 \
    libgraphene-1.0-0 \
    libgtk-3-0t64 \
    libgtk-4-1 \
    libharfbuzz0b \
    libpangocairo-1.0-0 \
    libx11-xcb1 \
    libxcb-shm0 \
    libxcursor1 \
    libxi6 \
    libxrender1 \
    libxtst6 \
    libsoup-3.0-0 \
    gstreamer1.0-libav \
    gstreamer1.0-plugins-bad \
    gstreamer1.0-plugins-base \
    gstreamer1.0-plugins-good \
    libegl1 \
    libenchant-2-2 \
    libepoxy0 \
    libevdev2 \
    libgles2 \
    libglx0 \
    libgstreamer-gl1.0-0 \
    libgstreamer-plugins-base1.0-0 \
    libgstreamer1.0-0 \
    libgudev-1.0-0 \
    libharfbuzz-icu0 \
    libhyphen0 \
    libicu76 \
    libjpeg62-turbo \
    liblcms2-2 \
    libmanette-0.2-0 \
    libnotify4 \
    libopengl0 \
    libopenjp2-7 \
    libopus0 \
    libpng16-16t64 \
    libproxy1v5 \
    libsecret-1-0 \
    libwayland-client0 \
    libwayland-egl1 \
    libwayland-server0 \
    libwebp7 \
    libwebpdemux2 \
    libwoff1 \
    libxml2 \
    libxslt1.1 \
    libatomic1 \
    libevent-2.1-7t64 \
    libavif16 \
    xvfb \
    fonts-noto-color-emoji \
    fonts-unifont \
    xfonts-scalable \
    fonts-liberation \
    fonts-ipafont-gothic \
    fonts-wqy-zenhei \
    fonts-tlwg-loma-otf \
    fonts-freefont-ttf \
  && apt-get clean
