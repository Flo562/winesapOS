FROM archlinux:latest

ENV OUTPUT_DIR /output
ENV WINESAPOS_ENABLE_PORTABLE_STORAGE false
ENV WINESAPOS_ENABLE_TESTING_REPO true

RUN \
    pacman --noconfirm -Syy && \
    pacman --noconfirm -S arch-install-scripts \
      base-devel \
      btrfs-progs \
      dosfstools \
      e2fsprogs \
      exfatprogs \
      parted \
      sudo \
      zip \
      zsh

WORKDIR /workdir/scripts
