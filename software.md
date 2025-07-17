---
layout: page
title: Software
subtitle: Data and software resources
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Software Packages | Your Lab Name</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: #f9f9f9;
        }
        
        .software-card {
            background-color: #f0f0f0;
            border-radius: 8px;
            padding: 25px;
            margin: 30px 0;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        
        .software-title {
            color: #2c3e50;
            margin-top: 0;
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
        }
        
        .btn {
            display: inline-block;
            background-color: #38231B;
            color: white;
            padding: 8px 15px;
            text-decoration: none;
            border-radius: 4px;
            margin: 5px 5px 5px 0;
            font-size: 14px;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #FDB91D;
        }
        
        .btn-secondary {
            background-color: #38231B;
        }
        
        .btn-secondary:hover {
            background-color: #FDB91D;
        }
        
        .software-image {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 4px;
            margin: 15px 0;
            display: block;
        }
        
        .badges {
            margin: 10px 0;
        }
        
        .badge {
            height: 20px;
            margin-right: 5px;
            vertical-align: middle;
        }
        
        .clearfix::after {
            content: "";
            clear: both;
            display: table;
        }
        
        .github-card {
            background-color: #010101;
            border-radius: 4px;
            padding: 10px;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="page-content">
        <div class="wrapper">
        	<!-- rpoCdb -->
            <div class="software-card">
                <h2 class="software-title">rpoC Database</h2>
                <a href="https://rpocdb.github.io/">
                    <img src="https://github.com/rpoCdb/rpoCdb.github.io/blob/main/assets/rpocdb_logo.png?raw=true" class="software-image">
                </a>
                
    		<p>rpoCdb is an interactive reference database designed for high-resolution microbiome profiling that provides:</p>
    		<ul>
       		 <li>Curated, high-quality full-length rpoC gene sequences</li>
      		  <li>Pre-formatted databases for commonly used microbiome software analysis pipelines</li>
      		  <li>Optimized wet-lab protocols</li>
       		 <li>Web-based taxonomy browser</li>
    		</ul>
    
          <a href="https://rpocdb.github.io/" class="btn">Access Database</a>

            <!-- MDM Histogram Tool -->
            <div class="software-card">
                <h2 class="software-title">Mutational Distance from Modal Haplotype Calculator</h2>
                <a href="https://aemann01.shinyapps.io/mdmhistogram/">
                    <img src="https://github.com/aemann01/aemann01.github.io/blob/master/assets/img/gitMDM.gif?raw=true" class="software-image">
                </a>
                
                <p>This interactive Shiny application uses STR repeat data from Y-chromosomal haplotypes to:</p>
                <ul>
                    <li>Calculate the modal haplotype from input data</li>
                    <li>Compute mutational distances for each individual from the modal haplotype</li>
                    <li>Generate publication-quality visualizations of the distribution</li>
                    <li>Provide statistical insights into population genetic patterns</li>
                </ul>
                
                <a href="https://aemann01.shinyapps.io/mdmhistogram/" class="btn">Launch Web App</a>
                <a href="https://www.frontiersin.org/journals/genetics/articles/10.3389/fgene.2024.1462736/full" class="btn btn-secondary">View Published Paper</a>
            </div>
            
            <!-- Bubble Tree -->
            <div class="software-card">
                <h2 class="software-title">Bubble Tree</h2>
                
                <p>Bubble Tree is a visualization tool that integrates:</p>
                <ul>
                    <li>Taxa frequency tables (rows as taxa, columns as samples)</li>
                    <li>Phylogenetic tree structures</li>
                    <li>Sample metadata</li>
                </ul>
                <p>to create either bubble tree visualizations or heatmaps displaying abundances plotted on phylogenetic trees.</p>
                
                <a href="http://github.com/aemann01/bubbleTree">
                    <img src="https://raw.githubusercontent.com/aemann01/bubbleTree/master/img/figexample.png" class="software-image">
                </a>
                
                <a href="https://github.com/aemann01/bubbletree" class="btn">View on GitHub</a>
                <a href="https://anaconda.org/aemann01/bubbletree" class="btn btn-secondary">Conda Package</a>
            </div>
            
            <!-- GC Content by Read Length Plots -->
            <div class="software-card">
                <h2 class="software-title">GC Content by Read Length Analysis</h2>
                
                <p>This tool provides comprehensive analysis of sequencing data by:</p>
                <ul>
                    <li>Calculating summary statistics for read length and GC content from FASTQ/FASTA files</li>
                    <li>Generating detailed statistics tables</li>
                    <li>Creating publication-ready visualizations of GC content by read length</li>
                </ul>
                
                <a href="http://github.com/aemann01/gcLenCorPlots">
                    <img src="https://raw.githubusercontent.com/aemann01/gcLenCorPlots/master/img/figexample.png" class="software-image">
                </a>
                
                <a href="https://github.com/aemann01/gcLenCorPlots" class="btn">View on GitHub</a>
                <a href="https://www.nature.com/articles/s41598-018-28091-9" class="btn btn-secondary">View Published Paper</a>
            </div>
        </div>
    </div>