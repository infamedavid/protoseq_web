# Protoseq Web

Static HTML/CSS site for Protoseq and Gina's ARP.

This version removes previous distribution links and presents the current product line:

- Protoseq Rack for VCV Rack
- Protoseq Plugin for CLAP/VST

Current placeholder download links:

- `VCV_LIBRARY_placeholder`
- `GUMROAD_CLAP_VST_placeholder`

## Structure

```text
/
  index.html
  style.css
  .nojekyll

/assets/
  protoseq-logo.svg
  protoseq-title.svg
  protoseq_mark.svg

/manual/
  index.html
  protoseq-rack.html
  protoseq-plugin.html
```

## Local preview

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```
