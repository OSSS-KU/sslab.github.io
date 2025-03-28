
<div style="padding: 40px;">
  <h1><strong>AI system software 🤹🏻</strong></h1>

  <p>In recent years, datacenters have evolved to accommodate a variety of heterogeneous workloads and devices. A prominent example is distributed deep learning training, which enables the development of large-scale AI models like GPT, DALL-E or LLaMA, demanding over 530 billion hyperparameters and utilizing hundreds of GPU nodes. As a result, optimizing infrastructure utilization and efficiency has become crucial. However, recent data from major cloud providers such as Microsoft and Alibaba reveal average GPU utilization rates of only 52.4% and 25.4%, respectively. This underutilization signifies a considerable waste of datacenter infrastructure resources, highlighting the need for more effective strategies to improve efficiency and utilization.

  One of the primary challenges in optimizing system infrastructure is that deep learning workloads have not yet been characterized by system software. Despite significant advancements in the field, determining the optimal training configuration, such as the GPU type and number of GPUs, remains unknown, resulting in unpredictable training times. This issue makes it impossible to optimize scheduling or system techniques on AI tasks. Also, severe overallocation of GPUs exist in datacenters. These resource inefficiency problems necessitate more efficient system management strategies.

  The following are representative technologies from our research.</p>

  <h1><strong>Network system software 🖥️</strong></h1>

  <p>Cloud computing is primarily realized through “networking,” which is utilized for either 1) device-to-device communication within a node or 2) node-to-node communication. In this context, the network infrastructure of datacenters must be virtualized to isolate performance and resource usage between tenants. However, current datacenters do not allow tenants to create or control their virtual network infrastructure, such as virtual switches, virtual links, and virtual topologies. Instead, the virtual network infrastructure is configured and managed solely by the datacenter administrators, which is in stark contrast to server virtualization. In particular, considering that customized operations of network resources (e.g., in-network computing) are one of the major building blocks of upcoming networking systems such as those beyond 5G, this issue is critical. As a result, system researchers have sought to make the network infrastructure controllable by "software" (known as software-defined networking, or SDN) to enable users of the network infrastructure to freely access, virtualize, and customize it (programmability).

  We are investigating network systems that are more 1) programmable, 2) high-performance, and 3) reliable for connecting heterogeneous devices and enabling services in this context. The following are examples of our technologies.</p>
</div>



<!-- ---
title: Tour
date: 2022-10-24

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Research
        content: 
        align: center
        # background:
        #   image:
        #     filename: coders.jpg
        #     filters:
        #       brightness: 0.7
        #   position: right
        #   color: '#666'
      # - title: Lunch & Learn ☕️
      #   content: 'Share your knowledge with the group and explore exciting new topics together!'
      #   align: left
      #   background:
      #     image:
      #       filename: contact.jpg
      #       filters:
      #         brightness: 0.7
      #     position: center
      #     color: '#555'
      # - title: World-Class Semiconductor Lab
      #   content: 'Just opened last month!'
      #   align: right
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Join Us
      #     url: ../contact/
    # design:
    #   # Slide height is automatic unless you force a specific height (e.g. '400px')
    #   slide_height: ''
    #   is_fullscreen: false
    #   # Automatically transition through slides?
    #   loop: false
    #   # Duration of transition between slides (in ms)
    #   interval: 2000
--- -->
