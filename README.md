fzf-bin
=======

Binary releases of [fzf](https://github.com/junegunn/fzf)

0.9.6 (2015/03/29)
------------------

[Download](https://github.com/junegunn/fzf-bin/releases/tag/0.9.6)

### Changes

- Added `--expect` option
- Fixed to ignore some ANSI escape sequences when `--ansi` is set
- Fixed `--ansi` option to retain ANSI background color

0.9.5 (2015/03/22)
------------------

[Download](https://github.com/junegunn/fzf-bin/releases/tag/0.9.5)

### Changes

- Added `--ansi` option
- Reduced initial memory footprint
- Fixed panic on `--no-sort --filter ''`

See [CHANGELOG](https://github.com/junegunn/fzf/blob/master/CHANGELOG.md#095)
for details.

0.9.4 (2015/03/01)
------------------

[Download](https://github.com/junegunn/fzf-bin/releases/tag/0.9.4)

### Changes

- Added `--tac` option for reversing the order of input
- `--no-sort` will not reverse the display order of items inside finder
    - *This is a backward incompatible change*
- `--filter` option will not block when sort is disabled (`--no-sort`)

0.9.3 (2015/02/18)
------------------

[Download](https://github.com/junegunn/fzf-bin/releases/tag/0.9.3)

### Changes

- Added `--sync` option for multi-staged filtering
- `--select-1` and `--exit-0` will start finder immediately when the condition
  cannot be met

