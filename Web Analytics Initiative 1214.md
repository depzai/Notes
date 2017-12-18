
##<span style="color:#FA9017">FAQ’s – Web Analytics in 2018: </span>
 
 
###<span style="color:#336BD3">Business Problem</span> 

We gathered use cases from stake holders in Marketing, BI, Data Science, in the US and DE. These initial conversations shed some more light on the need for an effective real-time web-tracking solution

Issues in the sytem's current implementation can be split into 2 categories:

- Technical instrumentation issues that prevent effective of the tool for day-to-day use
- Issues related to the architecture of the website and how we are set up as a company to maintain the tracking system

There are varying degrees of urgency in the issues: the proposed approach is to tackle some urgent issues first but also to look at a long-term, sustainable solution. A solution to this complex issue will require collaboration with stakeholders from the Marketing, Product, Tech and BI team, along with involvement from the vendor

####*1.What is the main business problem being addressed?*

-   We cannot answers the following questions: 
-   Losing money because on misallocation

####*2.Which teams are affected by the issue?*

####*3.What is the business impact we can expect from the initiative?*


###<span style="color:#336BD3">Short-Term Deliverables - Incremental Improvements</span> 

####*1.What are the most urgent issues to address?*

1. Projects / Work Streams with high dependencies on Web Analytics
2. Immediate Fixes needed

####*2.What is the proposed plan to address those?*

####*3.What is the proposed timeline?*

####*4.Who should be part of the work group?*


###<span style="color:#336BD3">Set-up Needed - Work Group</span> 

####*1.What is the Core Work group going to look like?*

- BI: Bruno Dupont / Bob Campbell
- Marketing: AJ Mihalic / Mael Borgers
- Product: Maddy Want / Web PM
- Tech: Ian Moraes or a team member

####*2.What is the extended Work group going to look like?*

This group will include exec sponsors from BI / Business / Product / Tech and will be consulted / informed on a monthly basis:

- BI: Cynthia Chu / Christian Herm
- Marketing: John Harrobin
- Product/Tech: Joe Berger / Mike Masiello / Rich Stern

####*3.What are the key deliverables we expect from the Core Work group?*

- Research and create the vision for the long-term plan
- Articulate the staffing needs and deliverables in the next 3-4 PI's

####*4.What is the proposed next step?*

- 1-week research phase with the whole Core Work Group in January


Workstreams: processes, tools, instrumentation

###<span style="color:#336BD3">Long-Term Solution</span> 
1. Vision - Issues to address

2. Project Scope

###<span style="color:#336BD3">FAQ Items – Deeper Dive:</span> 

####*1. Why Site Catalyst?*
There are a few key reasons why Site Catalyst is needed by Audible as a business:

- *Real-Time Data*: 
- *Full URL's*:
- *Built-in dashboards and excel plug in*
- *Action Codes for Visits*:
- *The tool is set up to manage sessions*
- *Creating customer segments*

####*2. How does it work?*

The tool is implemented by adding a few lines of specific code on each page of the website: that code will log traffic, events and customer information for each page into the Adobe database, which can then be used to build dashboard or to be ingested into DMART.

One of the biggest challenges of using this tool is that every page that needs tracking has to be instrumented with code specific to that page (a homepage and a product detail page would typically be insrtrumented differently)

####*3. What are the key Issues?*

Adobe Analytics is a very powerful tool that, if intrumented and maintained properly, could meet all of our needs in terms of web analytics. There are significant issues in our current version of the tool that prevents us from using it effectively. 

**Website Architecture**

We need clear vibility into the website's architecture in order to analyze performance using the following dimensions:

- Sections (e.g. Home, Library, Wish List, Browse, Listener Page)
- Page Types (e.g. PdP, MdP, Browse etc.): different Page Types will need different instrumentations
- Standardized Page Names: this is important to make our pages searchable using standard keywords

**Instrumentation Issues**

The following issues will most likely require changes to the instrumentation site-wide: 

- Referrers (SEO, PAid Search et.) not tracking correctly
- URL’s get truncated
- Some pages are not instrumented
- Instrumentation hasn't been updated on some pages
- Some events are not tracked on New Products (e.g. ass to library)

**Multiple Platforms**

Another major issue comes from the fact that our website is implemented on various platforms (Santana, ???, Simple Stack and now Arya), with different instrumentation on each platform. As a result, tracking on Santana pages cannot be compared to tracking on Arya pages for example.

However, since our website is in the process of moving entirely to Arya, this particular problem should go away by Q3-Q4 once the Arya migration is completed.

**Adobe Analytics on Arya**

The Arya migration includes Adobe Analytics instrumentation, meaning that every page migrated to Arya should be tracked in Adobe Anaytics. The issue, however, is that the instrumentation on Arya pages hasn't been tested.

It is imperative that we QA Adobe Analytics in Arya as soon as possible so we can address any issue (including the ones listed above).



