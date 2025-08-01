FROM node:22-slim

LABEL org.opencontainers.image.description "ACDH-CH frontend devcontainer"

RUN corepack enable

ENV COREPACK_ENABLE_DOWNLOAD_PROMPT=0
ENV DEBIAN_FRONTEND=noninteractive

# playwright dependencies
# @see playwright install --dry-run --with-deps
RUN \
  apt-get update \
  && apt-get install --no-install-recommends -y \
    libasound2 \
    libatk-bridge2.0-0 \
    libatk1.0-0 \
    libatspi2.0-0 \
    libcairo2 \
    libcups2 \
    libdbus-1-3 \
    libdrm2 \
    libgbm1 \
    libglib2.0-0 \
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
    libcairo-gobject2 \
    libdbus-glib-1-2 \
    libfontconfig1 \
    libfreetype6 \
    libgdk-pixbuf-2.0-0 \
    libgraphene-1.0-0 \
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
    libicu72 \
    libjpeg62-turbo \
    liblcms2-2 \
    libmanette-0.2-0 \
    libnotify4 \
    libopengl0 \
    libopenjp2-7 \
    libopus0 \
    libpng16-16 \
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
    libevent-2.1-7 \
    libavif15 \
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
