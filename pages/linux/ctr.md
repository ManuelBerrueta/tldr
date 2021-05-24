# ctr

> Manage Containerd containers and images.
> More information: <https://containerd.io>.

- Create a container:

`ctr container create {{image}} {{containerID}}`

- List all containers (running and stopped):

`ctr containers list`

- Delete a container:

`ctr container delete {{containerID}}`

- List all images:

`ctr images list`

- Pull an image:

`ctr images pull {{image}}`

- Tag an image:

`ctr images tag {{souce_image}}:{{source_tag}} {{target_image}}:{{target_tag}}`

- Remove an image:

`ctr image remove {{image}}`
