# vendor_to_product_manufacturer
Devices tree to OctOS
You have to create in vendor/to/product the fallow folders:
device/overlay/packages/apps/AboutOctOs/res/values/

Add in values the file strings.xml with yours change.

vendor/to/product/manufacturer/device
create to.dependencies and to.mk
he some of your device tree normal.

see my examples.

Done all and yours tree downloaded in source, now use this commands:

. build/envsetup.sh
brunch device
(device = you device)
