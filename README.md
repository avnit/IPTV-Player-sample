# IPTV-Player-sample

<!-- ARCH-DIAGRAM:START -->

## Architecture

> Auto-generated architecture diagram. See [`docs/context-map.md`](docs/context-map.md) for the full context map (core application, containers/cloud, and database connections).

```mermaid
flowchart TD
  User([User / Client])
  App["IPTV-Player-sample"]
  DB0[("Firestore (NoSQL)")]
  SVC0["Firebase / Firestore"]
  Deploy["GKE / Kubernetes"]
  User --> App
  App --> DB0
  App --> SVC0
  App -.deploy.-> Deploy
```

<!-- ARCH-DIAGRAM:END -->
