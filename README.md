# Kordian Zagaja

**Software engineer · Poland**

I build software across the stack—and increasingly beneath it: product interfaces, backend systems, native userspace, and operating-system infrastructure.

My commercial work has largely involved TypeScript and React product software, Node.js and Django backends, PostgreSQL, APIs, and delivery systems. My own engineering work is moving deeper into Rust and Linux because I like understanding the layers an application normally takes for granted.

## Current focus

I am building [**zeroOS**](https://github.com/KZagaja/zeroOS), an experimental Linux-based operating system with a Rust-native userspace for `x86_64` and `aarch64`.

The repository currently contains a dual-architecture UEFI boot flow, a static-musl Rust PID 1 with supervision and a versioned system API, plus storage, signed A/B update, rollback, and recovery machinery. Reproducible build inputs, dependency policy, architecture decisions, fuzzing, and native CI acceptance are treated as part of the system. It is pre-1.0: storage and release gates remain in progress, while the custom Wayland desktop and application platform are later milestones.

## Selected engineering work

### [zeroOS](https://github.com/KZagaja/zeroOS) · Rust / Linux

More than a distribution configuration: an attempt to own substantial userspace and product policy around the Linux kernel. It is where I work on boot, process supervision, image construction, update safety, recovery, trust boundaries, cross-architecture builds, and evidence-backed engineering decisions.

### [payments](https://github.com/KZagaja/payments) · Rust / Tauri / React

A desktop payment-terminal prototype that connects a React interface to native Rust serial-port handling. It includes USB device discovery, configurable serial communication, an ENQ handshake, and a mock device path; Bluetooth and a complete terminal protocol remain unfinished.

### [backend](https://github.com/KZagaja/backend) · Go / PostgreSQL

A domain-heavy Go API built with Fiber, layered services and repositories, SQL migrations, Redis-backed sessions, object storage, OAuth, and permissioned routes. The interesting part is the breadth of the data model and application boundaries rather than the framework itself.

### [ideacompiler](https://github.com/KZagaja/ideacompiler) · TypeScript / Next.js

A bilingual product site built with the Next.js App Router, typed localization, structured metadata, sitemap and canonical handling, a validated contact pipeline, and a small executable SEO check. It represents the product-facing end of my work.

## Engineering toolbox

**Systems:** Rust · Linux · UEFI · x86_64 / aarch64 · shell tooling

**Backend:** TypeScript · Node.js · NestJS · Fastify · Go · Django / DRF · PostgreSQL · REST · WebSockets

**Product:** React · Next.js · React Native · TanStack Query · Zustand / Redux · Tauri

**Delivery:** Docker · GitHub Actions · GitLab CI/CD · Jenkins · testing · profiling · release tooling

## How I approach engineering

- Understand the abstraction before depending on it.
- Make architecture and ownership boundaries explicit.
- Treat tests, CI, reproducibility, and recovery as system features.
- Prefer tools that fit the constraints over tools that happen to be fashionable.

## Beyond code

I hold a Master's degree in Law, which probably explains some of my interest in rules, edge cases, and how complex systems fail. Away from a terminal, I follow Formula 1 and pay attention to product and interface design.

## Contact

[ideacompiler.dev](https://ideacompiler.dev) · [contact@ideacompiler.dev](mailto:contact@ideacompiler.dev)

I am always interested in difficult engineering problems, ambitious software, and conversations with people who care how their systems actually work.
