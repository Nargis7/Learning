

# Mutable vs Immutable Infrastructure Notes

## Mutable Infrastructure

**Definition:** Infrastructure that can be changed or updated after creation.

**How it works:**

* Provision a server/system.
* Update it manually or automatically (patches, config changes, upgrades).

**Example:** Updating an existing server with new software.

**Pros:**

* Easy to make small changes.
* Flexible for quick fixes.

**Cons:**

* Risk of inconsistency.
* Harder to track changes.
* Configuration drift.

**Analogy:** Renovating a house — changing the interior but keeping the structure.

---

## Immutable Infrastructure

**Definition:** Infrastructure that cannot be changed after creation. To make changes, replace with a new version.

**How it works:**

* Build a new version of the server/application.
* Replace old version entirely.

**Example:** Deploying a new Docker container instead of changing the existing one.

**Pros:**

* Consistent environments.
* Easy rollback.
* Safer deployments.

**Cons:**

* Requires automated rebuilding.
* More initial resource usage.

**Analogy:** Replacing an old house with a completely new prefab house.

---

## Quick Memory Tip

* **Mutable = Change inside**
* **Immutable = Replace completely**

---

**Summary:**

* **Mutable** = Change things inside infrastructure.
* **Immutable** = Replace infrastructure entirely for any change.
