# Chapter 5 – First Boot

> **Status:** ✅ Verified on Hardware

---

## Learning Objectives

By the end of this chapter you will be able to:

- Boot the Duckiebot for the first time.
- Verify that the robot has successfully started.
- Access the Duckietown Dashboard.
- Verify that the onboard hardware has been detected.

---

## Estimated Time

10–15 minutes

---

## Prerequisites

- Ubuntu 22.04 LTS
- Duckietown Shell (DTS)
- 64 GB microSD card initialized with:

```bash
dts init_sd_card \
  --hostname duckieaskiegel \
  --type duckiebot \
  --configuration DB21J \
  --wifi NETGEAR94:Cooltrain323,iPhone:Cooltrain323 \
  --country US \
  --version default
```

