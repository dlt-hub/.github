![Scale Vector Header Version 1](https://github.com/scale-vector/.github/blob/main/Scale-Vector-Web-Banner-2.jpg)
 
If you’ve been fortunate enough to work for a startup company and a large corporate, you’d know that there are big differences between the two. Visiting a startup, you can’t help but noticing the magic in the air and everyone’s bright-eyed passion, ownership, creative thinking, sense of urgency, and speed of execution. Smaller teams have these in abundance, but as companies turn into corporations, they become slower, and people become comfortably numb.

At ScaleVector we think there needs to be a way to keep people focused on doing big things, while maintaining a startup atmosphere. That’s hard when you’re small, and impossible when you’re too big.

So we set out to support a new type of organization. One that tries to borrow from the good of both worlds — maturity and scale from corporations; agility, creativity and raw passion from startups. We think there's a next evolutionary step in the development of organizations, and it has to be invented and applied.

Did we mention that we aim to frequently open source chunks of our work? 

ScaleVector is currently working on the following set of related problems:

 ---
 
 <p>
  <img width="60" align='left' src="https://github.com/scale-vector/.github/blob/main/circle-1.png">
</p>
 
### Language Prediction Models In Enterprise Software Development 

We built a few prototypes to gain some understanding of language prediction models such as GPT3. In one of the working prototypes, a gpt-3 dialogue generation tool, we have learned how GPT-3 can be primed to generate human dialogue, which context it needs to perform well, some of limits of the model.
This application is now used in software development for exploratory/end to end testing.

 ---
 
 <p>
  <img width="60" align='right' src="https://github.com/scale-vector/.github/blob/main/circle-2.png">
</p>
 
### Data Pipelines For Complex Data

How should ingesting and structuring complex data (such as human language data) in an enterprise environment look like? 
We have shipped pipelines for AWS and GCP with generic schemas and metrics that enterprises can deploy within days.

Related problems:
- discovery and ingestion of JSON objects into databases
- transforming data into a semantic data model for human usage
- automatically writing a relational data store from a stream of documents

 ---
 
 <p>
  <img width="60" align='left' src="https://github.com/scale-vector/.github/blob/main/circle-7.png">
</p>
 
### Early ROI Of Your Enterprise AI Automation

When they start to deploy next-genaration AI automation enterprises often struggle to understand their ROI. From a business perspective they need this ROI to justify further investment and production roll-out.

At ScaleVector we are able to reverse ETL complex data into Google Analytics. This allows our enterprise clients to use their existing tools and workflows. 
On the client side setup does not require any configuration and developers devs, it can be done by the client's marketing team. We think of Google Analytics as a free solution for complex event analysis, a first step to a data store with further use cases.
 
 ---
 
 <p>
  <img width="60" align='right' src="https://github.com/scale-vector/.github/blob/main/circle-8.png">
</p>
 
### "Keep your notebook, use the enterprise data warehouse"  

Data scientists working on AI problems love to work in notebooks such as Jupyter Notebooks or Google Collab. 
At the same time it is difficult for them to access enterprise data with these tools and methods that are common to them such as Pandas.  

At ScaleVector we allow our clients to access their enterprise data in their notebooks via the Metabase API. 
Related problems:

- complex analysis and visualisation via the Metabase API
- Visual query builder for curated data, so you don't have to write complex SQL
- API access to a single source of truth

 ---
 
 <p>
  <img width="60" align='left' src="https://github.com/scale-vector/.github/blob/main/circle-4.png">
</p>
 
### Quantifying the level 3 assistants market among the Fortune 500  

The market for enterprise automation is booming, especially now that enterprises have to adapt to remote, work from home and hybrid office mode models. 
But what are the technologies adopted? To assess [level 3 assistant](https://rasa.com/blog/5-levels-of-conversational-ai-2020-update/) adoption among the Fortune 500 we are building:
- different approaches to scraping the data (Google vs the Linkedin API)
- experiments on how identify level 3 teams and the technology they use
- a classification and analysis layer

 ---
 
 <p>
  <img width="60" align='right' src="https://github.com/scale-vector/.github/blob/main/circle-3.png">
</p>
 
### Data models for AI Enterprise Teams  

Every company has this idealized vision of a AI, data science and analytics team, with full visibility into how the business is doing, how the product gets used, how experiments are performing. The problem with getting there (and this is part of why data teams don’t get hired until later in the company lifecycle) is that the actual, cold hard data that you need to answer important questions typically lies all over the place. And it needs cleaning. 

Data teams write intermediate SQL queries that format source data in a way that makes it easier to answer  high level questions. A few examples of those kinds of transformations:
- Aggregating all of the different types of product events into one table that keeps track of product state.
- Arranging your Stripe data to calculate MRR by month
- Grouping website visits into “sessions” for easier analysis

Mature data teams will have hundreds of these kinds of transformations. When you group all of these together, you’ve got what is called a data model.

We help clients by building models of 90% of their data with a tool called dbt. dbt is a toolset for building data models. It lets data teams run SQL to build models, add documentation to each table, manage the semantic schema deployment, run tests to ensure data quality, and many other nice things. Without customization enterprise data pipelines are unusable. With our dbt packages it is easy for our clients to customize pipelines of the remaining 10% of data so they can use the pipeline.

 ---
 
 <p>
  <img width="60" align='left' src="https://github.com/scale-vector/.github/blob/main/circle-6.png">
</p>
 
### Towards Negative Data Engineering  

Companies have an idealized vision of how data engineers work, as well. Observationally data enginners spend 50% of their time fixing broken data pipelines. Negative engineering is usually not done in data. Negative data engineering is when engineers write defensive code to make sure the positive code actually runs. Negative engineering is characterized by needing to anticipate this infinity of possible failures.

By leveraging past experiences, we created a simple framework for resilient pipelines. We are in the early innings of having of some of our data engineering friends testing it. 

 ---
 
 <p>
  <img width="60" align='right' src="https://github.com/scale-vector/.github/blob/main/circle-5.png">
</p>

### Gamers first, again ?   

While a lot of automation happens in the enterprise, we are also curious about other affected industries. From our own experience we know that often it is game developers that are usually the first to deploy new technologies en masse before everyone else. 

Based on that insight we running some experiments. Can we apply some of the enterprise-grade automation on gaming platforms such as Discord?  


