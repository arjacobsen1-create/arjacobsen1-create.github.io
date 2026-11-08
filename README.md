# arjacobsen1-create.github.io

The root site for Anahita Jacobsen's GitHub Pages. It is the front
door for the published tools and the host of the domain's
Digital Asset Links file (`.well-known/assetlinks.json`), which the
Token Estimator Android app (Trusted Web Activity) uses to verify
ownership of this domain.

- **Token Estimator** — AI cost planning and optimisation:
  https://arjacobsen1-create.github.io/token-estimator/

The Token Minimiser also exists as a standalone site in its own
repo (token-minimiser), retained public; it is not featured on the
landing page because the Minimiser is the third module of Token
Estimator, and the front door tells that one story.

The asset-links file ships empty until the Android signing key
exists; its contents (package name + SHA-256 fingerprint) are added
during Google Play packaging.
