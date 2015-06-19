---
permalink: /environments/
layout: default
title: Environments
---
## Do developers have access to production equivalent development environments?

Functionally identical environments are required for reliable development and
testing.

**Comment:** _Depends on self-service, benefits from elasticity. Enables
automatic promotion #3._


## Do developers have access to snapshots of production data in their development environments?

Functionally identical data is required for reliable development and testing.
This is a separate question since it’s typically going to be a more
significant ask from the perspective of security.

**Comment:** _Depends on self-service, benefits from elasticity. Enables
automatic promotion #3._

## Can applications be promoted between environments with changes to their environment variables alone?

This implies good, secure, stateless application design. It’s an important
part of a complete CD train.

**Comment:**
**Dependency:** CD, automation, version controlled configuration.
