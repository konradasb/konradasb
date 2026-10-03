System Engineer at [Hostinger](https://www.hostinger.com). By day I keep public
clouds and Kubernetes clusters from doing what they would naturally do. By
night I write the software I wish existed. In between, I'm a dad of one son:
the only on-call rotation with no escalation path.

### Currently building

- **[Dicer](https://github.com/konradasb/dicer)** · [dicer.sh](https://dicer.sh)\
  Dices bare metal into thousands of micro VMs, booted straight from container
  images. Because containers are great right up until someone says
  "isolation" in a meeting.
- **[Rungar](https://github.com/konradasb/rungar)** · [rungar.sh](https://rungar.sh)\
  GitHub Actions runners, a fresh machine for every job, on Dicer, Proxmox,
  GCP or AWS. Your CI deserves better than a shared runner with someone
  else's `node_modules` on it.

They fit together: Rungar runs each job in its own Dicer micro VM. Call it
vertical integration, or call it not trusting anyone else's software.

### Also lying around

- **[ansible-collection-general](https://github.com/konradasb/ansible-collection-general)**\
  Ansible roles for all of the above, because I install things by hand exactly
  once.
- **[systemd-resolved-exporter](https://github.com/konradasb/systemd-resolved-exporter)**\
  Prometheus metrics for systemd-resolved, because "it's always DNS" deserves a
  dashboard.

### Stack

Shorter to list what I haven't worked with:

- a YAML file that was right the first time
- a "temporary" fix that stayed temporary
- Windows Server, on purpose
- a cloud bill nobody asked questions about
- COBOL
- Oracle, because I don't want to be that guy

Everything else, from the kernel up to the Kubernetes control plane, I have
probably broken and fixed at least once.

### Reach me

[LinkedIn](https://www.linkedin.com/in/konradasb/). I reply faster than your
`terraform plan`.
