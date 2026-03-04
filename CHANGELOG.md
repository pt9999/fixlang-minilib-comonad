## 0.7.0
### Breaking Changes
- Minilib.Comonad.Env:
  - Uncurried arguments of `env_t`, `env`.
  - Changed internal structure.
  - Changed `Comonad::extend` implementation.
  - Changed the kind of type alias `Env` to `* -> *` to prevent `Env e` from giving a "not fully applied" error.
- Minilib.Comonad.Traced:
  - Changed the kind of type alias `Traced` to `* -> *` to prevent `Traced e` from giving a "not fully applied" error.
- Minilib.Comonad.Store:
  - Changed the kind of type alias `Store` to `* -> *` to prevent `Store p` from giving a "not fully applied" error.
### Fixed
- fixed tests.

## 0.6.2
- Added `Minilib.Trait.Dual`.
- Added `Minilib.Comonad.IOStore`.
- Depends on minilib-common@0.12.3, minilib-monad@0.11.1.

## 0.6.1
### Added
- Added `Minilib.Comonad.Cofree`, `Minilib.Comonad.Store`.

## 0.6.0
### Changed
- fixproj.toml: Bumped `fix_version` to 1.3.0. Depends on minilib-common@0.12.0, minilib-monad@0.11.0.
### Added
- Added CHANGELOG.md.
