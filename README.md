# Docker Katas
Some [katas](https://en.wikipedia.org/wiki/Kata) for using [docker](https://www.docker.com/).

The intent here is to create a training aid for new and forgetful Docker users. We've mostly just pulled these together from around the internet, out of books, or made them up. If you see something missing and you'd like to contribute, please feel free to create a [Pull Request](https://help.github.com/articles/creating-a-pull-request/) on this repo.


## Recommended Order For Learning

1. [Pull and Run an Image](1_pull_and_run_image.md)
2. [List Images](2_list_images.md)
3. [List Containers](3_list_containers.md)
4. [Delete Container](4_delete_container.md)
5. [Delete Image](5_delete_image.md)
6. [Named Containers](6_named_containers.md)
7. [Start Containers](7_start_containers.md)
8. [Tag an Image](8_tag_an_image.md)
9. [Delete and Image by Tag](9_delete_image_by_tag.md)
10. [Execute Command In Container](10_exec_in_container.md)
11. [Change The State of The Container](11_change_container_state.md)
12. [Commit Changes](12_commit_changes.md)
13. [Interacting With Containers](13_interacting.md)
14. [Pushing Images](14_pushing_images.md)
15. [Create An Image for a Python Application](15_simple_python_image.md)
16. [Create An Image for a Ruby Application](16_simply_ruby_image.md)
17. [Setting Environment Variables](17_setting_envvars.md)
18. [Overriding Environment Variables](18_overriding_envvars.md)
19. [Publish Network Interfaces](19_publish_network_interfaces.md)
20. [Mounting Volumes](20_mounting_volumes.md)
21. [Defining Your Network Interface](21_define_network_interface.md)
22. [Defining Your Volume](22_define_volume.md)


<!-- Upcomming content
[Pushing Images] 
https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes
[Force shell on bad entrypoint] docker run -it -v test:/docker_kata_vol --entrypoint sh ps_out:latest
[Remove Volume] AND OTHER Volume things!
[Remove all Dangling Images] docker rmi $(docker images -f dangling=true -q)
[Remove all Images] docker rmi $(docker images -a -q)
[Remove all Exited Containers] docker rm $(docker ps -a -f status=exited -q)
-->

## By Command

<TODO>
