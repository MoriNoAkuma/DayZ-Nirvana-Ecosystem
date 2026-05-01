# Changelog

## [In progress]
- Expanding payment options
- Clearing specific player statistics (global)
- Discord shop system improvements: option to add product images, discount display, promo code support
- Moving the information panel to .json for easier updates

# v1.0.0-rc.1
## Implemented
- Full bot settings management via the web panel
- JSON product creation system via the web interface
- Skeleton loaders for the website

----------------------------------------------------------------------------------------------------------

# v1.0.0-rc.2
## Implemented
- !!Realisation of buying `Queue Priority`
- Page optimization

## Hotfixes
- Debug mode now can be turned on via admin panel on web-site
- Fixed: active players were incorrectly removed from the online list after stale session reconciliation.

----------------------------------------------------------------------------------------------------------

# v1.0.0-rc.3
## Implemented
- !!Realisation of dynamic Discord ticket constructor via the web panel (up to 5 custom fields)
- Smart synchronization for linked promo codes (auto-updates rewards on the DayZ server upon template changes)
- Ephemeral (private) rating system for closed tickets to prevent admin abuse
- Dynamic hot-reloading for the LIS_Promocodes path (no bot restart required)
- Added strict SteamID validation (numbers only) for ticket forms
- Web panel UI/UX improvements (visual ticket constructor, form limits) and updated docs

## Hotfixes
- Fixed: DonationConfig attribute error when saving settings from the web constructor
- Fixed: Metadata integrity loss (ProductID & DisplayName) during item delivery or case unboxing