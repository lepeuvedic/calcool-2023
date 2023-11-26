---
title: Natixar Real Time Carbon Accounting Help
date: 2023-11-26T15:53:44.106Z
description: Natixar offer a real-time carbon accounting
  software-as-a-service  solution to all the businesses confronted with the need
  to reduce their carbon  footprint while expanding their operations. Because
  the adaptations to climate change are transformational for most businesses,
  our tool provides analyses  and guidance in the form of projects.
image: https://static.wixstatic.com/media/11062b_d578b9d4ffba48c68d086ec29fe9e6f0f000.jpg/v1/fill/w_1309,h_429,al_c,q_85,usm_0.33_1.00_0.00,enc_auto/11062b_d578b9d4ffba48c68d086ec29fe9e6f0f000.jpg
---
# Problem Statement

As a manufacturing facility operator, or as a business owner, you have greater control over greenhouse gas emissions than most people, and with this, also comes a greater responsibility to fight climate change. But too often, you only have a preconceived ideas of your emission sources and of the amount of emissions your activities are generating.

The first action is to understand how your activities generate direct and indirect emissions of greenhouse gases. The second action, is to analyze the changes you can make at any level in your organization to reduce your impacts. But as you keep developing your business, you will find it difficult to reduce the net emissions, and you will need to calculate more advanced metrics like the product environmental footprint, which allocates emissions to each product or service leaving your facilities.

# Installation

## Configuration

Contact us using the [form](https://www.natixar.com/contact-5).
We will decide together how our software uses and stores your data, whether you need it to run in the cloud or on-premises, and which options best suit your needs. You will be able to add options as your company grows at a later stage, too.

## Onboarding

Since our software automates the collection of data, we have to understand how it can access your organization's data. In industrial companies, this typically involves a connection with your production planning software or inventory software. 

We will also preload two years of historical data in our emissions database. Depending on your requirements, we will run our software in the public clouds, or on premises in a micro-cloud. Static, generic resources like this documentation page, are typically downloaded from content delivery networks on the Internet.

Finally we will request your authorization to collect utilities data on your behalf from the grid operator and other utility network operators as necessary. This action gives us access to designated utility meters registering your organizations energy consumptions.

# Projects

Our software revolves around projects, small and big. 

## Reports and Awareness

An example of a small project is your contribution to national reporting of emissions through the creation of a standards-conformant table of your company's GHG emissions. Our tool generates documents that put your data in relation to global warming trends, and can be used for motivation campaigns and general education to the climate change issues. The information we provide through this channel is regularly updated.

## Process Digitization

We also digitize processes, that are in direct relation to environmental impacts, like the maintenance of systems, which use cooling fluids or other regulated chemicals having a strong environmental impact. Because the systems, measuring tools and maintainer are often the same, we can automate the boilerplate and collect environmentally relevant data at the same time. A project can be started for each such system. The first task is a configuration task, defining the system and editing QR-codes. The second task is a periodic maintenance task. 

## Decarbonization Projects

A bigger project would be to work with one of our decarbonization partners, to reduce the carbon footprint of your operations. We have partners to explore the solar potential or your site, partners focusing on reducing single-use packaging, partners offering energy-recovery solutions, and many others.

# Insights

Real-time data collection enables you to pinpoint the leading emission sources in your organization. We organize your emissions data in a data lake, with the structure of a multidimensional cube. The baseline dimensions are **time** and **nature**. Depending on your needs, you can expand your setup with **impact**, **geographic**, **organizational** and **production** dimensions. 

## Data Model

### Production dimension

The production dimension gives you access to a custom hierarchical description of your production system, and enables you do associate environmental impacts with the most precise piece of equipment responsible for it. If you measure combustion exhaust from a particular vehicle, based on its measured fuel combustion and engine characteristics, this impact source can be traced to that particular vehicle. Of course the dimension is a hierarchy and you can associate impacts at any level, depending on their nature and the available knowledge. 

For instance, a track system can be shared by a number of vehicles, and be a piece of a larger transportation system. Track maintenance operations are not direct contributors to production, and instead, those impacts are allocated to each production shuttle. 

This dimension maximizes the benefits you might be getting from the digital twin of your factory and your IoT system. The detailed description of your production processes that is optionally linked to this dimension is a key to two optional capabilities: 

* Allocation of impacts to individual products or services taking into account the latency of your production processes
* The Life Cycle Impact Analysis of your products (together with impact dimension)

### Organization Dimension

In large organizations, it is useful to track decarbonation progress according to organizational perimeters. This can be especially helpful when managers have environmental goals.

The organization dimension is a hierarchy. Each environmental impact is associated with a specific entity in your organization.sites

This dimension is structured in a hierarchy, with one or more levels of groups at the top, decomposed in affiliated companies and economic entities (for example a shop location). You have full control over the structuration of this dimension, which is revision controlled to ensure that past emissions from old entities remain properly accounted for.

### Geographic Location Dimension

National authorities often request data aggregated at national level, and if you operate an international organization, this dimension will help you correctly aggregate the data. Large companies typically have some large view of the world split in a few world regions, like Americas, EMEA and Asia. The next hierarchical level is usually the countries. It is possible, but usually unnecessary, to provide more detail between countries and sites. In most countries our software understands the address and associates it to the correct geographical location. City, county, land and other local subdivisions are automatically deduced.

The geographic dimension gives you the possibility to split a site in distinct production units. This is useful for large sites hosting multiple distinct production units.

If you have multiple production units on the same site and an energy management system, its data can be used to allocate impacts to each unit.

### Impact Dimension

Our baseline solution helps you track regulated greenhouse gas emissions. There are many greenhouse gases, but our database holds all emissions in the unit of emitted carbon dioxide equivalent (kgCO2eq).

On rare occasions, the conversion factors between CO2 and other greenhouse gases are corrected. The source data is always saved in order to enable such updates. For instance, the amount and nature of a cooling fluid leaked from a system is always remembered. Therefore, if the climate impact of this specific fluid is updated, we will recalculate your past emissions correctly.

Many systems have multiple types of emissions and multiple impacts beyond the emission of greenhouse gases into the atmosphere. The impact dimension lets you add to your data cube, ESG impacts not limited to greenhouse gas emissions. The current options computes the detail of emissions of the most common greenhouse gases: CO<sub>2</sub> from fossil or biological sources, CH<sub>4</sub> from fossil or biological sources, NO<sub>2</sub>, others. New functionality packages will expand the possibilities of our tool, using new data connectors to track all the ESG impacts described in the CSRD regulation and to compute the associated KPIs.

### Time Dimension

All the stakeholders want to see greenhouse gas emissions decline over time, so the time dimension is a core dimension in the Natixar tool. The time dimension is preconfigured and internally uses a unified time coordinate with an accuracy of one second.

The time dimension is currently preconfigured with the prevalent scheme, which allows both per week and per month views. Data can be aggregated at any scale: minutes, hours, days, weeks, months, quarters and years.

### Nature Dimension

This dimension is built in the baseline version of our tool. It associates each emission with a category in the unified carbon emissions plan. Tool users can choose between Bilan Carbone and GHG Protocol reporting schemes to aggregate emissions in various conventional ways. These conventions are meant to compare organizations with each other, although this remains difficult, and also to track consistently the emissions of a company, while it transforms itself into a low carbon organization.

The classification groups emissions in scopes, with scope 1 being direct emissions, usually from the combustion of hydrocarbon fuels, scope 2 indirect emissions triggered elsewhere due to the local use of energy, typically electricity, and scope 3 being all the indirect emissions that have already occurred or that will occur later, after the products are delivered to the customer.

## Data Analysis

A data cube provide a convenient framework to analyze data. The current version offers predefined views that we can customize to suit your needs. We can customize the views to match any customer's requirements, and we aim to deliver user-customizable dashboards soon.

In the Natixar solution a data cube has only two dimensions: the __time__ and the __nature__ of GHG emission source. The general principle for visualization, when working with a cube, is to pick one dimension as the main dimension, and to aggregate all the other dimensions. 

For example, if the time dimension is chosen, emissions of all natures are summed and the result is a 2D curve of emissions over time. The time dimension has one particularity: it is one-dimensional and oriented, and therefore well suited to draw curves. If the nature dimension is chosen first, the result will be a bar chart with all known emissions gathered by nature, and aggregated at the desired level of the hierarchy. Assuming the top level is chosen, the bar chart will show the split of all emissions per scope. If a relative view is desired, a pie diagram will be used instead. The pie diagram shows the percentage each scope represents.

Any visual element, like a bar in a bar chart or a pie slice in a pie chart can be selected and further analyzed in the same fashion. A single visual element is a cut through the data cube, retaining only the elements having the corresponding value for some defined coordinate. Of course, the hierarchical nature of axes simplifies the selection of multiple related cuts, thereby defining the concept of a slice.