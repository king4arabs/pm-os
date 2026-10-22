# Dependency migration — validation pending

The dependency graph was resolved with Composer security blocking enabled. A Packagist audit of the resulting lockfile reported zero known security advisories on 2026-10-22. No advisory exceptions were added. Platform extensions were ignored only during dependency resolution; installation must verify the real runtime and extensions.

The repository lacks artisan, bootstrap/app.php and an application test suite. Complete application bootstrap and tests before merging. Review Inertia 2, OpenAI client, PDF and query-builder major-version changes.

This branch has not been application-tested or deployed. A clean dependency audit does not prove application security or compatibility.
