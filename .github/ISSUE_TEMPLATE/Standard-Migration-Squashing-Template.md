---
name:  Migration Squash
about: Use this template to create an issue to squash all migrations
labels: Technical
---

# Description
We have 10 or more migration files

## Negative Impact:
This causes QA script, and general project initialization to slow down costing us developer hours

# Proposed Solution:
Squash migrations down into the init_schema directory of the migrations directory. 
Create new migration classes as necessary.
Update `InitialDatabaseSchema::MOST_RECENT_MIGRATION_NAME` to the latest migration name on production DB
Update the date on the file name of `yyyy_mm_dd_000000_initial_database_schema.php` 

## Acceptance Criteria
- [ ] Production schema is NOT modified in any way
- [ ] All migrations created prior to the creation of this issue are squashed down into the initial_migration folder.
- [ ] The init_schema file should be renamed to reflect today's date
- [ ] Production migrations table is updated to reflect this new, single flattened migration

## Announcement Message

dev-important:
All migrations have been squashed, please rebase/merge to/from master to have a consistent project initialization.
< LINK TO PR GOES HERE >
