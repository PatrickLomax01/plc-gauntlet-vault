# plc-gauntlet-vault
# PLC Gauntlet – Unlock the Vault

An interactive web page for Newcastle High School's **PLC Gauntlet** professional learning activity.

Staff work in teams to solve six "rooms" based on the PLC model:

1. PLC Purpose – **EVIDENCE**
2. PLC Norms – **ACTION**
3. Impact Cycle – **274**
4. Instructional Rounds – **BASELINE**
5. Roles (ELT, Coordinators, PLC Leaders) – **LEAD**
6. Term 1 PLC Sequence – **REFINE**

When all codes are entered correctly, the vault reveals the final phrase:

> `COLLECTIVE EFFICACY UNLOCKED`

## Running the site

This is a single static HTML file and can be hosted with **GitHub Pages**.

1. Create a new public repository, e.g. `plc-gauntlet-vault`.
2. Add `index.html` and `README.md` to the repository.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Save. After 10–30 seconds your site will be live at:

`https://<your-username>.github.io/plc-gauntlet-vault/`

## Customising

To change codes, room names, or the final vault phrase, edit the `locks` array
and `VAULT_PHRASE` constant in the `<script>` block of `index.html`.
