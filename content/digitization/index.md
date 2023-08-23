---
title: "Digitization"
#date: 2022-07-22T08:08:18+01:00
draft: false
type: benefits

---

Our mission is to simplify the digitization of production environments. Eclipse BaSyx provides a robust and scalable infrastructure for digital twins, and integrate numerous applications that support many kinds of digitization tasks. This includes components to create, monitor, and host Asset Administration Shells (AAS), integrate them with their real-world assets and provide easy-to-use dashboards. The Eclipse BaSyx Data Bridge connects AAS with assets to create Digital Twins that represent the asset state at all times, and optionally enables controlling of assets and processes. The Eclipse BaSyx AAS Web UI visualizes AAS out of the box – optionally, add custom visualizations by leveraging its plugin mechanism.

Eclipse BaSyx is however not limited to the AAS – we additionally provide software components to support creation of dashboards, automating tasks, to implement condition monitoring systems, and to enable efficient production of small lot sizes. This is what we call the service-oriented production, and it yields easily changeable manufacturing processes. 

When you use our Open Source middleware, the Asset Administration Shell will become a unified interface for all of your assets, enabling them to communicate, exchange data, and to start negotiations. This enables future applications – think about digital market places, and autonomously adapting supply chains – start digitizing your production today!

 
## Digitize your factory with Asset Administration Shells & Digital Twins

- <b>Asset Administration Shell (AAS) Implementation:</b> Eclipse BaSyx is the reference implementation for the Asset Administration Shell (AAS), which is the standardized foundation for <a href="https://www.iese.fraunhofer.de/en/services/digital-twin.html" target="_blank">Digital Twins</a>. 

- <b>AAS submodels:</b> Eclipse BaSyx supports both AAS and AAS submodels. AAS submodels provide views to assets, which include data and services required for realizing specific use-cases. The same AAS may consist of multiple submodels, and more submodels may be added over time to increase the number of supported use-cases. 

- <b>Registry:</b> The AAS & Submodel registries keep track of communication endpoints and connects AAS/Submodel users to the endpoints based on the AAS/Submodel ID. An AAS or Submodel may be addressable through multiple IDs to support e.g. addressing via unique IDs, IDs of customers, serial numbers, and much more. 

- <b>Repository:</b> Repositories store AAS and AAS submodels. Create multiple repositories to keep the AAS and AAS submodels wherever you need them. Both can be kept in different repositories to make sure that all data and e.g. relevant data pre-processing algorithms are kept in submodels close to the process, while AAS are stored in data centers.

- <b>DataBridge:</b> The DataBridge connects real-world assets to AAS with a large number of supported protocols. The Eclipse BaSyx DataBridge is extensible, supports integration of new protocols and is even configurable for non-experts. 

- <b>Scalability:</b> Our architecture supports multiple backends for AAS registries and repositories, including file systems, SQL and NoSQL databases. Therefore, your Eclipse BaSyx installation will scale with the size of your production lines. As we strictly separate front-end from back-end services, Eclipse BaSyx supports both horizontal and vertical scalability. You may setup for example multiple AAS repositories, and use them as independent hosts for AAS, or connect them with a load balancer to distribute the load on many servers. Eclipse BaSyx provides a solid, scalable solution that runs on embedded devices, desktop machines, and datacenters. We furthermore support file systems, and numerous SQL and NoSQL database engines to store data. Choose the backend that you need and let Eclipse BaSyx grow with your business.

- <b>Smart AAS:</b> You yourself decide about the kind of AAS that you want to realize. While today many AAS provide access to data, Eclipse BaSyx can do much more. An AAS may implement services that process, convert, and aggregate values to implement high-level interface. Device controllers realize unified interfaces to setup and control assets – and hide device-specific aspects. Even autonomous behavior and negotiations between AAS is possible, if you choose to enable it. Why not setting up a unified digital infrastructure with <a href="https://www.iese.fraunhofer.de/en/services/digital-twin.html" target="_blank">Digital Twins</a>?

- <b>Digital Twins:</b> Use the DataBridge component to integrate devices with your AAS and its submodels to create <a href="https://www.iese.fraunhofer.de/en/services/digital-twin.html" target="_blank">Digital Twins</a> for your Assets. The Eclipse BaSyx DataBridge supports this with numerous protocols, which include for example OPC UA, MQTT, Modbus, Ethernet/IP, ProfiNET and many more. As bidirectional communication is possible (but not obligatory), your <a href="https://www.iese.fraunhofer.de/en/services/digital-twin.html" target="_blank">Digital Twins</a> therefore may also control devices and change parameters if this is desired.

- <b>Flexibility:</b> Create Asset Administration Shells and AAS submodels for any kind of Asset – devices, processes, products, IT systems – the choice is yours. The Asset Administration Shell will serve as unified interface to all your assets, and will integrate them into one digital world. Additionally, all components of BaSyx are highly configurable and can be easily extended.

- <b>Tried and Trusted:</b> Eclipse BaSyx is already today part of manufacturing lines and projects all around the globe. There exists a multitude of <a href="../success-stories/">reference projects</a> where BaSyx is delivering benefits every day. As of today, our components were downloaded more than 100.000 times!

- <b>Supported by a strong Ecosystem:</b> If you ever need help in utilizing Eclipse BaSyx, our strong <a href="../partners/">ecosystem of partners</a> is ready to support you in every step towards Industry 4.0. 



## One virtual Dataspace – simplify analysis and monitoring tasks

- <b>One Virtual Dataspace:</b> Factory digitization requires the integration of all data and services. Eclipse BaSyx creates one virtual dataspace that provides unified access to services and data. This includes data from devices, products, processes, IT-Systems, and all other relevant assets. 

- <b>Dashboards and virtual control rooms:</b> Eclipse BaSyx integrates Eclipse Streamsheets and Grafana – two open source tools that are integrated with Eclipse BaSyx supports the creation of dashboards and virtual control rooms. Both aggregate data from different sources, visualize the factory and production lines, and support identification of optimization potentials. As all data is available through one harmonized interface, you can aggregate and combine it as you wish. And if our provided tools are not sufficient, our simple HTTP/REST API enables integration of any other application. 

- <b>Autonomously react to Events:</b> No need to monitor device states and sensors anymore. Use Eclipse BaSyx to autonomously react to events. With the integrated node.RED open source tool, you can detect events and define automated reactions, for example pushing of a cellphone event. There is no need to check machine states manually anymore!   

- <b>Integrate new Assets:</b> Integrating of new assets into the virtual dataspace is simple as well. Just create an Asset Administration Shell (AAS) for your asset, set up the AAS submodels to reflect properties and services, and use the data bridge component to connect to your assets – without writing a single line of code!



## Digital Product Passports, PLM Systems, Product Carbon Footprint, and so much more

- <b>Digital Twins for Everything:</b> Eclipse BaSyx supports the creation of Digital Twins – of course for your devices and manufacturing lines, but also for processes, products and everything else. Your digital twins represent their real-world asset at all times, and may contain all relevant data that has been collected throughout its production and lifecycle.  

- <b>PLM Systems:</b> Share product data with PLM systems, integrate all data into the Eclipse BaSyx dataspace, and provide important data back to PLM systems to improve the development of future products.

- <b>CO2 footprint:</b> With Eclipse BaSyx, you are ready for future applications. Aggregate production data from the virtual Eclipse BaSyx dataspace to enable future CO2 footprint calculations, thus enabling you to provide the product carbon footprint of your assets. But why stopping at the calculation of product carbon footprints? Use your data to identify optimization potentials, and reduce the CO2 footprint of your products, as well as corresponding energy costs.

- <b>Digital Product Passport:</b> A digital product passport contains all relevant product data. This includes production quality data, supplier information, and potentially also recycling information. When digitizing your manufacturing processes with Eclipse BaSyx, you are ready to create Digital Product passports. 


## Unified Interfaces 

- <b>Unified interfaces:</b> Eclipse BaSyx integrate all of your assets into one virtual dataspace. It also provides a unified, HTTP/REST based API to access device data and services. This greatly simplifies the development and integration of new applications, and is the foundation for digital manufacturing. 

- <b>Control component:</b> Control components are a unified interface for controlling devices, and an important precondition for creating digitized processes. Control components enable to set the operation mode of a device, query the device status, setting of parameters, and to locate failures quickly. 

- <b>Software versions:</b> Which device is running vulnerable software versions? An average manufacturing line consists of hundreds of devices – keeping track of software versions for each device is a challenge on its own. Asset Administration Shells and Digital Twins support digital nameplates that keeps track on software version, which help with locating devices that e.g. need updating.

- <b>Stepwise integration:</b> Using the Asset Administration Shell does not require a big-bang migration of your existing systems. Instead, Eclipse BaSyx supports structured migration paths with its highly configurable and adaptable components to ensure the best support for an iterative approach. Unlock business value at every stage of your migration to Industry 4.0!


### Digital Supply Chains & Lot-Size 1 Production

- <b>Changing markets:</b> Customer demands and markets change frequently. Competitive advantage is increasingly defined by the ability to quickly adapt to changes. Eclipse BaSyx provides the building blocks to create Service-Oriented manufacturing environments. Develop PLC functions as re-useable services, and orchestrate them with BaSyx. Change your products in minutes, and integrate new devices in hours instead of days.

- <b>Participate in digital supply chains:</b> Exchange data with stakeholders and stay in control. You can serialize individual AAS submodels, and even create new AAS for exchanging information. This way, you decide which data you share with others, and what you keep for yourself. 

- <b>Automated Documentation:</b> Customers demand increasing amounts of documentation. Eclipse BaSyx creates digital processes with digital twins for devices and products that enable automatic documentation of product and process quality.

