# Why this fork exists

An organisation-owned fork of `psf/requests`, kept so mo-eval can mine a Python benchmark from a
repository that is actively merging pull requests — and so its results are visible to the whole
organisation rather than to one person, since access is scoped by a repository's OWNER.

`.mo-eval/config.toml` names the UPSTREAM as `repo`: the merged pull requests mined here are
upstream's, not this fork's.
