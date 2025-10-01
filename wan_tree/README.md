# WAN Colab Experimental Tree

This directory isolates the `WAN_ClownShark_Realistic_Waifu_Setup.ipynb` notebook so it can evolve on its own branch without touching the legacy "leštěnka" work that remains on `main`.

Suggested workflow:

1. Create and check out a dedicated branch before editing the notebook:
   ```bash
   git checkout -b wan-colab-experiments
   ```
2. Iterate on `WAN_ClownShark_Realistic_Waifu_Setup.ipynb` from inside this `wan_tree/` folder.
3. Keep the main line clean by merging only when the WAN setup is ready.

No code has been modified—only the project layout now separates the WAN notebook from the existing materials.
