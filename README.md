# Free VPN — VLESS server list

This repository stores VLESS connection links collected from a Song69 VPN subscription shared by the repository owner.

## Files

- `servers.txt` — five unique VLESS links, one per line. Import the file or copy a link into a VLESS-compatible client such as v2rayN, v2rayNG, or another Xray/VLESS client.
- `README.md` — this guide and the source/validation notes.

## Servers included

| Label | Host | Port | Notes |
|---|---|---:|---|
| Germany — Optimal | `qcloudge1.exitvpn.shop` | `20268` | Original subscription also listed this same endpoint as “Germany — Free”; it was deduplicated. |
| France — Free | `fr.song69.fun` | `443` | VLESS over TCP with REALITY security |
| Poland — Free | `pl1.song69.fun` | `443` | VLESS over TCP with REALITY security |
| Sweden — Free | `sweedenqfds777.qcloud.surf` | `21221` | VLESS over TCP with REALITY security |
| Finland — Free | `finkawwwbroy5.qcloud.surf` | `20324` | VLESS over TCP with REALITY security |

## Source and processing

The connection details were copied from the Song69 subscription content supplied by the repository owner in chat. The original subscription URL is intentionally not reproduced here because it contains a subscription token. Six entries were supplied; two entries pointed to the same German endpoint with the same connection parameters, so `servers.txt` contains five unique configurations.

The links retain the supplied UUID and connection parameters, including flow, transport, REALITY public key, SNI, fingerprint, and short ID where present. Server labels are descriptive names based on the supplied labels/hostnames.

## Validation status

- File was read back from GitHub after upload.
- The five links were checked for basic VLESS URL structure and the expected connection fields.
- **Live connectivity has not been verified.** A structurally valid link does not guarantee that the server is online, that the subscription is still active, or that the credentials remain valid.

## Security note

This repository is public. Anyone who can view it can copy the connection links and UUID. Do not publish private subscription URLs or credentials unless you intend to share access. If these links are personal, consider making the repository private and asking the provider to rotate/reissue credentials if they have been exposed.

## Import

1. Download `servers.txt` from this repository.
2. In a VLESS-compatible client, import the file or add a link from the file.
3. Test each server in the client; availability may change over time.
