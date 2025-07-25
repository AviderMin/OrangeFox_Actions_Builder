# OrangeFox Action Builder
Compile your first custom recovery from OrangeFox Recovery using Github Action.

# How to Use
1. Fork this repository.

2. Go to `Action` tab > `All workflows` > `OrangeFox - Build` > `Run workflow`, then fill all the required information:
 * MANIFEST_BRANCH (`12.1` and `14.1`)
 * DEVICE_TREE (Your device tree repository link.)
 * DEVICE_TREE_BRANCH (Your device tree repository branch.)
 * DEVICE_PATH (`device/vendor/codename`)
 * DEVICE_NAME (Your device codename)
 * BUILD_TARGET (`boot`, `recovery`, `vendorboot`)

 # Note
* This action will now only support manifest 12.1 and 14.1, since all orangefox manifest below 12.1 are considered obsolete.
* Make sure your tree uses right variable (updated vars) from OrangeFox; [fox_14.1](https://gitlab.com/OrangeFox/vendor/recovery/-/blob/fox_14.1/orangefox_build_vars.txt) and [fox_12.1](https://gitlab.com/OrangeFox/vendor/recovery/-/blob/fox_12.1/orangefox_build_vars.txt), to avoid build erros.

 # Actions workflow
* Thanks [@ymdzq](https://github.com/ymdzq/OrangeFox-Action-Builder)