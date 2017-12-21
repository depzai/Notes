##<span style="color:#FA9017">Web Analytics - 2018</span>

###<span style="color:#336BD3">Introduction - Business Problem</span>

We gathered use cases from stake holders in Marketing, BI, Data Science, in the US and DE. These initial conversations highligted significant issues with our current tracking system.

Site Catalyst (Or Omniture, Adobe Analytics) is the tool currently used for tracking visits and event on web surfaces. Issues in the sytem's current implementation can be split into 2 categories:

- Technical instrumentation issues that prevent effective of the tool for day-to-day use
- Issues related to the architecture of the website and how we are set up as a company to effectively maintain a web tracking system

There are varying degrees of urgency in the issues: the proposed approach is to tackle some urgent issues first but also to look at a long-term, sustainable solution. A solution to this complex issue will require collaboration with stakeholders from the Marketing, Product, Tech and BI team, along with involvement from the vendor.


####*1.What is the main business problem being addressed?*

At high level, Marketing and BI teams are encountering data issues when using Site Catalyst to track visits and events:

-   Visits are getting misallocated across some acquisition channels
-   Tracking of visits and events is not possible on new products (such as Romance)
-   Tracking of visits and events on new features (such as pdp redesign) is unreliable
-   The Trial Take Rates we derive from our visit tracking are unreliable
-   We cannot **reliably** answer the following business questions:
    +   Where do our visits come from on mobile web?
    +   How many visits does audible get in a given period on our website?
    +   How many visits does a given subset of the audible website get in a given period?
    +   What percentage of those visits materialize in a membership event
    +   What is the exact URL a given visit originated from?

####*2.Which teams are affected by the issue?*

- **Marketing Team**: these issues prevent accurate forecasting and website performance monitoring (e.g. purchase rates on new titles or promotions). Accurate visit tracking is also critical for channels like SEO to develop and scale further as acquisition channels.
- **BI/Data Science Team**: key projects need accurate tracking to be completed, including the Multi-Touch Attribution Model, the Purchase Journey model and the Media-Mix Model. 
- **Product / UX Team**: the Product BI relies heavily on that data for reporting and feature performance monitoring.

####*3.What is the business impact we can expect from the initiative?*

- Improved visibility into our traffic and external traffic sources and:
    + Accurate Visit and TTR reporting on all channels
    + Acquisition Optimization for the affected channels (SEO, Anon)
- Improved Performance Tracking on new products / features
- Improved AB Testing capabilities
- More accurate BI analyses and tools such as MTA, Purchase Journey, MMM

###<span style="color:#336BD3">Short-Term Deliverables - Incremental Improvements</span> 

####*1.What are the most urgent issues to address?*

- Issues have been identified with the current implementation of the Site Catalyst tool that prevent marketing and BI teams from using it effectively. Since all webpages are being migrated to Arya, we need to make sure that the Site Catalyst implementation on the Arya platform meets our business needs.
- Additionally, an issue with action code allocation methodology is causing discrepancies in how we recognize units in SEO, Anon and Paid Search in particular
    
####*2.What is the proposed plan to address those?*

- **Arya Audit**:
    + *Implementation Review*: detailed review of the logic used for the Site Catalyst implementation with the Development team. The idea is to understand what we should expect to flow through the tracker in as much detail as possible.
    + *Tracking Audit*: this step would be a user test that would involve a BI team member with Site Cat experience to check that the tracking is working as expected on Arya pages. The recommended scope would include a sample set of pages from US, Canada and DE. This step might also require help from a Site Catalyst consultant.
    + *List Issues and Recommended Fixes*: based on the audit, the team will provide a list of fixes needed to ensure Site Catalyst can be used effectively on the Arya platform
    + *PI5 Epic*: the fixes will be submitted  for prioritization as an Premium epic in PI5
- An **Action Code Epic** to address the allocation methodology for visits was submitted for prioritization in PI4: confirmation is pending on when this epic will be tackled by the Web team.

####*3.What is the proposed timeline?*

- The Arya audit is scheduled for PI4, with fixes implemented in PI5
- The work group will work on the vision and plan for the long-term solution through PI4.

####*4.Who should be part of the work group for this phase?*

- BI analyst(s) with Site Catalyst expertise to conduct the audit
- Marketing Lead (tbd)
- Site Catalyst consultant (tbc)
- Web Developer / SDM to provide clarity on the logic used for Site Cat in Arya (Jeff Deutsch tbc)

###<span style="color:#336BD3">Set-up Needed - Work Group</span>

####*1.What is the Core Work group going to look like?*

Here is a proposed structure for the core work group:

- BI: Bruno Dupont / Bob Campbell
- Marketing: AJ Mihalic / Regina Markantes / Mael Borgers?
- Product: Maddy Want / Web PM
- Tech: Ian Moraes or a team member

####*2.What is the extended Work group going to look like?*

This group will include exec sponsors from BI / Business / Product / Tech and will be consulted / informed on a monthly basis:

- BI: Cynthia Chu / Christian Herm
- Marketing: John Harrobin
- Product/Tech: Joe Berger / Mike Masiello / Rich Stern

####*3.What are the key deliverables we expect from the Core Work group?*

- Research and create the vision for the long-term plan in terms of:
    + Processes
    + Tools
    + Instrumentation
- Articulate the staffing needs and deliverables in the next 3-4 PI's

####*4.What is the proposed next step?*

- 1-week research phase with the whole Core Work Group in January


###<span style="color:#336BD3">Long-Term Solution</span> 

####*1.What is the vision for this long-term solution?*

The detailed vision for a sustainable, best-in-class web tracking solution will have to be developped by the Core Work Group based on input and use cases from the business, BI, product and tech teams.

Below are 2 directional routes the company could go in order to ensure improvements in the way audible tracks traffic and events on web surfaces.

*Option 1 - MEDIUM - Best Practices to facilitate tracking going forward*

Once the Arya audit is done and potential fixes are in place, tracking should be at an acceptable level on web surfaces. The priority will then be to ensure continuity going forward. This can be addressed with a set of best practices around new pages / feature launches, including for example:

- Architecture practices including URL, page name and page type conventions
- Tagging, including standardized ref markers conventions
- Standardized documentation and communication practices around each new page/feature launch

*Option 2 - LARGE - Web Tracking Overhaul*

In this option, we'll explore reshaping how we approach website tracking at audible by tackling some of the main issues that were identified in the initial discovery phase, including:

- Website Architecture:
    + Page types
    + Standardized Page names / URL's
- Maintenance:
    + Integration of new events
    + Integration of new pages
- Data Management:
    + Data Quality process
    + Extracts into DMART


####*2.What is the scope of this initiative?*

*Option 1 - MEDIUM - Best Practices to facilitate tracking going forward*

This project involves mostly processes and can be tackled in 2 phases, with an initial research spike and then implementation, probably around PI5. Ownership in the Product Management organization will be critical.

*Option 2 - LARGE - Web Tracking Overhaul*

Going this route will have to turn this project into a full-fledged initiative, with high product-management involvement needed and collaboration between BI, Marketing, Product and Tech teams.

####*3.What are the key milestones to hit in 2018?*

To be determined in the initial research phase.

###<span style="color:#336BD3">FAQ Items – Deeper Dive:</span> 

####*1. Why Site Catalyst?*
There are a few key reasons why Site Catalyst is needed by Audible as a business:

- *Real-Time Data Feeds*
- *Tracks Full URL's*
- *Built-in dashboards and excel plug in*
- *Can apply Action Codes to Visits*
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

- Referrers (SEO, Paid Search et.) not tracking correctly
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


##<span style="color:#FA9017">NOTES</span>

COMMENTS:
Issue is that visits for natural search peaked on Oct 23, coinciding with pdp roll out on arya:

- Sample pdp and look at traffic:
- is traffic elsewhere also dropping
- is it inconsistent with trial trends?
- Also traffic dropped after that but it shouldn't (entering holiday season)
- Also: traffic by action code seems to be higher than by referrer when it should be exaclty the same
- prop17 is needed to filter by member / non member.
- Looks like post_evar38 can also be used for that
- ref_domain seems to be the referrer website (e.g. google.com)
- prop5 is the action code
- prop4 if detail page or other

Action codes:

- OSTS0001WS062909 google: a lot of hits with this action code don't have a ref domain (should be google)
- OSTS0003WS062909
- OSTS0002WS062909
- OSTS0011WS071509
- ANONAUDW0378WS010202

Huge peak on nov 14 2017, no evar / prop give any clue so far

###<span style="color:#336BD3">Actions Needed / Questions:</span> 

**DMART DATA**

- Need all props and evar migrated over

**CONSULTANT**

- Session on logic / data structure
- How to replicate a dashboard like SEO QA with DMART data

**WEB TEAM**

- What is the implementation in Arya:

**TESTING**

- Against clickstream, using a page with reliable tracking / ref markers
- Uses cases using test id's on different page types

Mike M: having a TPM
Cynthia:
Send out the comm. on status, timeline


