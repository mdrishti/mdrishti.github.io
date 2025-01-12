---
layout: default
title: Research
permalink: /research/
---
<div id="research" class="tab active">
  <h1>My Research</h1>
  <p>My time during Bachelors/Masters as a student and my research career during PhD/Postdocs, provided me exposure to a range of research topics and technical skills. This allowed me to explore the fundamental challenges in biodiversity, microbiome and omics disciplines through the lens of data science. You can find my career and education details on my LinkedIn profile.</p>


<div class="featured-container">
  
  <!-- Card 1 -->
  <div class="content-card_res">
    <a href="#binpairs" class="card-link">
      <img src="https://cdn.ncbi.nlm.nih.gov/pmc/blobs/224a/4281075/3ec48b4ee89c/pone.0114814.g001.jpg" alt="Binpairs" style="height: 200px; object-fit: cover;">
    </a>
      <div class="content-text">
  <h3>Beginnings</h3>
  <p>My first research project was to find common threads in a couple of algorithms that find the best taxonomic matches of paired sequencing reads to microbial genomes. I developed simple, yet effective strategies to utilize this information for improved binning.</p>
      </div>
  </div>

  <!-- Card 2 -->
  <div class="content-card_res">
    <a href="#arm" class="card-link">
      <img src="https://journals.plos.org/plosone/article/figure/image?size=inline&id=10.1371/journal.pone.0154493.g005" alt="Association Rule Mining" style="height: 250px; object-fit: cover;">
    </a>
      <div class="content-text">
  <h3>Microbial interactions</h3>
  <p>I became deeply involved in investigating microbial interactions beyond pairwise approaches. I adapted the apriori association rule mining algorithm to investigate microbial interactions from relative abundance data,</p>
      </div>
  </div>


  <!-- Card 3 -->
  <div class="content-card_res">
    <a href="#prebiotics" class="card-link">
      <img src="https://journals.plos.org/plosone/article/figure/image?size=large&id=10.1371/journal.pone.0195643.g006" alt="Prebiotics-1">
      <img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1038%2Fs41598-019-41837-3/MediaObjects/41598_2019_41837_Fig2_HTML.png" alt="Prebiotics-2">
    </a>
      <div class="content-text">
  <h3>Tryst with prebiotics</h3>
<p>Together with my colleagues, I embarked on a collaborative project with Tata Chemicals Limited, where we investigated the 16S rRNA based microbiota composition analysis of one of the first Indian cohorts.</p>
</div>
   </div>
  
<!-- Card 4 -->
  <div class="content-card_res">
    <a href="#nanopore" class="card-link">
      <img src="https://www.biorxiv.org/content/biorxiv/early/2023/12/05/2023.12.05.570138/F1.medium.gif" alt="Nanopore" style="height: 200px; object-fit: cover;">
    </a>
      <div class="content-text">
  <h3>Fascinating nanopore sequencing</h3>
    <p>I established a rapid and affordable pipeline, suitable for small-scale composition analysis of low-complexity microbiota using long-read nanopore sequencing. This approach is useful for small-scale laboratories at academic or commercial levels and does not require expensive investments in high-end equipment.</p>
   </div>
   </div>

<!-- Card 5 -->
  <div class="content-card_res">
    <a href="#evolution" class="card-link"><img src="/assets/images/mevolution.jpeg" alt="Microbial evolution">
    </a>
      <div class="content-text">
 <h3>Microbial evolution</h3>
 <p>I explored the long-term evolution (>4 years) of a potential live vaccine candidate in the murine intestinal tract. I demonstrated that multiple genomic evolutionary trajectories can result in the same phenotype, although with differing genomic or epigenomic factors. Contrary to the expected outcome of mutated genomic virulence factors,</p>
 </div>
 </div>

<!-- Card 6 -->
  <div class="content-card_res">
    <a href="#trydb-globi" class="card-link"><img src="/assets/images/biodiv.jpeg" alt="Biodiversity knowledge management" style="height: 200px; object-fit: cover;"></a>
      <div class="content-text">
 <h3>Fitting pieces of biodiversity data – metabolomes, traits and interactions</h3>
 <p>I developed a knowledge graph integrating data from 3 repositories - TRY plant traits database, Global Biotic Interactions (GloBI), and Experimental Natural Products Knowledge Graph (ENPKG). The end-users including researchers, science journalists and stakeholders in science policy-making can use this resource and establish meaningful insights into the biodiversity of plants.</p>
 </div>
 </div>
 </div>


<!-- Full descriptions for each project -->
<section class="project-descriptions">
<div id="binpairs" class="project-description">
  <h3>Beginnings</h3>
  <p>The trajectory of my career has been unconventional. After a usual Bachelors-Masters route, I joined TCS Innovation Labs (now known as TCS-Research). There, I was introduced to the world of metagenomics - the whole genome, the controversial 16S rRNA, and the rest of it.</p>
  <p>My first project in TCS was to find common threads in a couple of algorithms that find the best taxonomic matches of paired sequencing reads to microbial genomes (technical term for the match-finding process is binning). Several of these algorithms did not use the pairing-information efficiently. Along with my colleagues, I developed simple, yet effective strategies to utilize this information for improved binning.</p>
</div>

<div id="arm" class="project-description">
  <h3>Microbial interactions</h3>
  <p>Typically, microbial interactions, i.e., their co-occurrence patterns, are predicted by employing pairwise correlation coefficient measures like Pearson, Kendall, Spearman, Kullback-Leibler distance, or dissimilarity measures like Bray Curtis. A variety of algorithms and statistical tools are available for visualizing and analyzing networks which provide valuable biological insights with respect to pairwise microbial interactions. Such insights help in understanding the metabolic exchanges that potentially occur between the identified member pairs. However, in reality, the complexity of microbial interactions surpasses simple pairwise correlations.</p>
<p>I adapted the apriori association rule mining algorithm to investigate microbial interactions from relative abundance data, thus deriving rules that explain the complex sub networks in microbial communities. Using real-world microbiome data, I demonstrated the utility of this rule mining approach in deciphering multiple biologically meaningful association patterns between subsets of microbes. As an example, association rules derived from publicly available gut microbiome datasets indicate an association between a group of microbes (Faecalibacterium, Dorea, and Blautia) that are known to have mutualistic metabolic associations among themselves. Application of rule mining approach on gut microbiomes (sourced from the Human Microbiome Project) further indicated similar microbial association patterns in gut microbiomes irrespective of the gender of the subjects.</p>  
</div>

<div id="nanopore" class="project-description">
  <h3>Fascinating nanopore sequencing</h3>
  <p>16S rRNA amplicon sequencing is conventionally used to identify and determine the relative abundance of bacteria in microbial communities. 16S rRNA is a special gene, in the sense that even though it is conserved across multiple bacteria, it is variable enough to detect the differences in the different species. But this detection is a tricky businees.</p>
<p>Deep amplicon sequencing of complex microbiomes is well established using short-read sequencing targeting variable regions of the 16S rRNA gene. Third-generation long-reads sequencing technologies like nanopore sequencing have made it possible to sequence full-length 16S rRNA genes. Short reads enable accurate classification of bacteria until the genus level in taxa hierarchy, whereas long reads provide better chances of identification to lower levels such as species and even strains. However, for the latter, a benchmarked, robust, fast, and cost-effective approach starting from DNA extraction to accurate compositional analysis has been missing. To this end, I established a rapid and affordable pipeline, suitable for small-scale composition analysis of low-complexity microbiota using long-read nanopore sequencing (preprint available). I used 16S rRNA gene full-length (~1500 bp) amplicons from a low-complexity bacterial community derived from the intestinal content of gnotobiotic (defined microbial communities with known microbes) mice. I developed a bioinformatics pipeline to process the long-read amplicon reads and classify them to species level. This approach is useful for small-scale laboratories at academic or commercial levels and does not require expensive investments in high-end equipment.</p>
</div>

<div id="evolution" class="project-description">
 <h3>Microbial evolution</h3>
 <p>In recent years, live vaccines have proven to be an effective measure for preventing infection from gastrointestinal pathogens. However, long-term safety and efficacy of vaccines has not been well studied. With emerging reports and pioneering work about microbial evolution from multiple researchers, it has become clear that even under seemingly constant environments, microbes evolve with aid of natural selection, genetic drift, clonal interference and bottlenecks.</p>
 <p>I explored the long-term evolution (>4 years) of a potential live vaccine candidate in the murine intestinal tract. I demonstrated that multiple genomic evolutionary trajectories can result in the same phenotype, although with differing genomic or epigenomic factors. Contrary to the expected outcome of mutated genomic virulence factors, I showed that often mutations occur in regulatory regions that control microbial virulence and metabolite transport. This work involved in-depth exploration of genomics data generated using both short-reads (Illumina) and long-reads (PacBio). I also established a pipeline to detect epigenetic patterns from the long-reads PacBio sequencing data.</p>
</div>

<div id="trydb-globi" class="project-description">
 <h3>Jumping into the realm of knowledge management</h3>
<p>Advances in plant biology research have led to numerous studies into studies like plant traits measurement, determining their interactions with surrounding biodiversity, and their metabolic profiling. While many of these studies have been successfully completed, the associated data lies fragmented in various formats within the peer-reviewed research, supplementary information and datasets on public repositories. These circumstances necessitate that a comprehensive knowledge graph be created to establish links between these data. I employed a linked open data approach to establish appropriate data formats and ontologies for plant datasets. I developed a knowledge graph integrating data from 3 repositories - TRY plant traits database, Global Biotic Interactions (GloBI), and Experimental Natural Products Knowledge Graph (ENPKG). This resource will soon be integrated in the Digital Botanical Garden Initiative’s knowledge graph (part of Earth Metabolome Initiative). The end-users including researchers, science journalists and stakeholders in science policy-making can use this resource and establish meaningful insights into the biodiversity of plants.</p>
<p>Ongoing development on this project can be found at the following github repositories - rdflib_trydb_globi, DBGI/integrate_trydb_globi_enpkg, and DBGI/earth_metabolome_ontology.</p>
<p>After spending 10 years in microbiome science, this project was a welcome break to learn new skills and combine my new and old knowledge to develop a resource that will be useful for the microbiome science across the world. More about that in the coming days - watch this space!</p>
</div>
</section>

</div>
