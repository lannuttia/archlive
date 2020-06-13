FROM archlinux

RUN pacman -Syu --noconfirm \
  # Install packages required to build ISOs from releng profile.
  # See https://gitlab.archlinux.org/archlinux/archiso.git for more details.
  && pacman -S --noconfirm \
    archiso \
    git