# Update Ceph Image Script

Run the `update-ceph-image` script to update Rook-controlled CephCluster resources in your
Kubernetes cluster to the latest SUSE Enterprise Storage version. The script will not update
Rook-Ceph cluster which are not currently running an image from a SUSE registry.

## images directory
Images in the images directory contain the latest images with tags from SUSE to be used for SUSE
Enterprise Storage. You can use these images in your own scripts if desired.
