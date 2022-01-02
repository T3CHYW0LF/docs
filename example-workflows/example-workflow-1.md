---
description: Using tomnomnom's tools for recon..
---

# Example-Workflow-1

## Steps

### assetfinder

```
assetfinder -subs-only priceline.com > domains
```

### httprobe

```
cat domains | httprobe | tee -a hosts
```
