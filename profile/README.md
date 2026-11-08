[![HopOS, HOP and SURF — Run the machine. Run the jobs. Bring them to the screen.](https://raw.githubusercontent.com/hop-os/.github/main/profile/banner.png)](https://gethop.org)

**Three small things for people who run their own metal.**

An operating system written in Rust, a small orchestrator and a distributed desktop. Each has a clear job. Together, they take you from bare hardware to running services and windows across machines.

[Website](https://gethop.org) · [Documentation](https://gethop.org/hopos/docs/) · [Get in touch](mailto:hello@gethop.org)

### Get started with HopOS Imager

**[HopOS Imager](https://github.com/hop-os/hop-imager)** is the easy way to get a node running: one desktop app to **write an image, configure your board and find your nodes**. No terminal needed.

1. **Burn** — choose a release and board, then write and verify your SD card or USB stick.
2. **Configure** — set the node name, cluster and startup jobs.
3. **Find** — discover your nodes on the network.

**[Download HopOS Imager](https://github.com/hop-os/hop-imager/releases/latest)** · [See how it works](https://github.com/hop-os/hop-imager#readme)

### Start with the piece you need

| Project | Its job | Explore |
| :--- | :--- | :--- |
| **[HopOS](https://github.com/hop-os/HopOS)** | Run the machine. A bare-metal OS in Rust, with hardware-enforced memory partitions and a shared app ABI for Rust and Go. | [Overview](https://gethop.org/hopos/) · [Docs](https://gethop.org/hopos/docs/) |
| **[HOP](https://github.com/hop-os/hop)** | Run the jobs. Place, update and recover processes, Docker containers and HopOS apps through one job model. | [Overview](https://gethop.org/hop/) · [Docs](https://gethop.org/hop/docs/) |
| **[SURF](https://github.com/hop-os/HopOS-surf)** | Bring them to the screen. Apps draw on one machine; a display app brings their windows together on another. | [Overview](https://gethop.org/surf/) |

### Around the core

- **[hoplock](https://github.com/hop-os/hoplock)** — lease-based leader election backed by S3 conditional writes.
- **[hopqueue](https://github.com/hop-os/hopqueue)** — a single-binary job queue with SQLite, HTTP/SSE and S3 leader election.

Start with the [HopOS documentation](https://gethop.org/hopos/docs/) to explore the system, or [HOP](https://gethop.org/hop/) to orchestrate existing Linux and macOS machines. Questions and bug reports belong in the relevant project's issues.

Built by **[Haas Software](https://haas.software)** · More tools at **[@haas-software](https://github.com/haas-software)**.
