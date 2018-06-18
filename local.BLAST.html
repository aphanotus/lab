---


---

<h1 id="local-blast">Local BLAST</h1>
<p>This document describes how to run command-line <a href="https://www.ncbi.nlm.nih.gov/books/NBK279680/">BLAST</a> with custom search-able databases on <a href="https://www.colby.edu/arc/hardwaresystems/computer-clusters/nscc/">Colby’s <strong>nscc</strong></a>.</p>
<h2 id="running-blast-on-nscc">Running BLAST on <strong>nscc</strong></h2>
<p>“<a href="https://www.ncbi.nlm.nih.gov/books/NBK279690/">BLAST+</a>” is a suite of linux programs that run the different variations of the <a href="https://en.wikipedia.org/wiki/BLAST">basic local alignment search tool (BLAST) algorithm</a>. Which program (<code>blastn</code>, <code>blastp</code>, <code>blastx</code> or <code>tblastn</code>) you need to run depends to whether your search query is a nucleotide or amino acid (protein) sequence and whether you’re searching a database of nucleotide or protein sequences.</p>
<p><img src="https://www.bugsinourbackyard.org/wp-content/uploads/2018/06/blast.types_.jpg" alt="BLAST varieties"></p>
<p>Once you know the variety of BLAST you need, the basic form of the command is:</p>
<pre><code>blastn -query /path/input.filename.fa -db /path/BLASTdb &gt; output.filename
</code></pre>
<p>Notice that the default is for BLAST to send its output to “stdout”, that is, the screen. So typically you want to redirect that output to a named file.</p>
<p>Here’s a more realistic example.</p>
<pre><code>tblastn -query /research/drangeli/BLAST_DBs/query_sequences/Dmel.act5C.fa \
  -db /research/drangeli/BLAST_DBs/Nlug.CDS.BLASTdb/Nlug.OGSv1-0.CDS.BLASTdb \
  &gt; Dmel.act5c.vs.Nlug.OGSv1-0.CDS.tblastn.txt
</code></pre>
<p>Notice a few things about this command.</p>
<ul>
<li>The input files are all identified by their complete path from root. I do this because the query files and the databases are typically in different folders, and this keep things organized.</li>
<li>The output file has no path. In other words the i,mplied path is <code>./</code>. So, I typically run the BLAST command from the folder where I want the output file to be.</li>
<li>The output file name has built into it several important pieces of information:
<ul>
<li>the name of query sequence,  <code>Dmel.act5C</code>, in this example</li>
<li>the name of the database,  <code>Nlug.OGSv1-0.CDS</code></li>
<li>the type of BLAST, <code>tblastn</code></li>
<li>the <code>.txt</code> extension should make it clear that this is human-readable output</li>
</ul>
</li>
</ul>
<h3 id="a-note-on-digital-species-abbreviations">A note on digital species abbreviations</h3>
<p>In order to keep things organized on <strong>nscc</strong>, it’s helpful to use consistent and clear file names. For species, they are typically identified by a four letter abbreviation consisting of the first initial of the genus, followed by the first three letters of the specific epithet. So, <em>Oncopeltus fasciatus</em> becomes <code>Ofas</code>.</p>
<p>There are a few exceptions to this rule. The pea aphid, <em>Acyrthosiphon pisum</em>, would become <code>Apis</code>, which would certainly get confused with the honeybee genus, <em>Apis</em>. So the aphid community has adopted <code>Acypi</code> as their digital handle.</p>
<h2 id="custom-blast-databases">Custom BLAST databases</h2>
<p>Below is a list of paths to each of the custom <a href="https://www.ncbi.nlm.nih.gov/books/NBK279680/">BLAST</a> search-able databases available to our lab group on <code>nscc</code>. Custom BLAST databases each reside in a folder, but consist of several different files (with the extensions <code>nhr</code>, <code>nin</code>, <code>nog</code>, <code>nsd</code>, <code>nsi</code>, and <code>nsq</code>). To run <a href="https://www.ncbi.nlm.nih.gov/books/NBK279680/">BLAST</a> from the linux command line, you will need to refer to the path of the database and the base name of those files. List the contents of the database folder if you’re not sure what this looks like.</p>
<h3 id="oncopeltus-fasciatus"><em>Oncopeltus fasciatus</em></h3>
<p>This is the reference transcriptome that was used to annotate the <em>O. fasciatus</em> genome project. The CDS (coding sequence) FASTA file was kindly provided by <a href="https://warwick.ac.uk/fac/sci/lifesci/people/kpanfilio/">Kristen Panfilio</a>. When she shared the file, Kristen told us the data originate from “pooled Illumina RNAseq reads from mixed juvenile, adult male, and adult female libraries”. But we have no more specific information about the ages of those individuals. We might be able to follow-up with Kristen about that.</p>
<pre><code>/research/drangeli/BLAST_DBs/Ofas_transdecoder_cds/Ofas.TR.BLASTdb
</code></pre>
<h3 id="jadera-haematoloma"><em>Jadera haematoloma</em></h3>
<p>This database is built from the ‘grand union’ of transcripts assembled from samples of the Plantation Key ecotype from whole bodies, dorsal thorax and gonads of first day adults. It is the most complete <em>J. haematoloma</em> transcriptome we have and is estimated (by <a href="https://busco.ezlab.org/">BUSCO</a>) to include 89% of conserved genes.</p>
<pre><code>/research/drangeli/BLAST_DBs/Jhae_GU_BLAST_DB/Jhae.GU.TRassembly.BLASTdb
</code></pre>
<p>Additionally, we have transcriptomes and BLAST databases for samples from male and female gonads (testes and ovaries). I’m not sure if the testes also included the accessory glands.</p>
<h4 id="j.-haematoloma-females"><em>J. haematoloma</em> females</h4>
<pre><code>/research/drangeli/BLAST_DBs/Jhae_ovary_BLAST_database/Jhae.ovary.TRassembly.BLASTdb
</code></pre>
<h4 id="j.-haematoloma-males"><em>J. haematoloma</em> males</h4>
<pre><code>/research/drangeli/BLAST_DBs/Jhae_testes_BLAST_database/Jhae.testes.TRassembly.BLASTdb
</code></pre>
<h3 id="jadera-sanguinolenta"><em>Jadera sanguinolenta</em></h3>
<p><a href="http://www.soapberrybug.org/01_cms/details.asp?ID=72"><em>J. sanguinolenta</em></a> is a seperate species of soapberry bug whose range overlaps that of <a href="http://www.soapberrybug.org/01_cms/details.asp?ID=65"><em>J. haematoloma</em></a> in South Florida. They are not know to hybridize in the wild and attempts to do so in the lab have not produced offspring. <em>J. sanguinolenta</em> is not known to produce short-wing morphs in the wild, but they have appeared in the lab, suggesting a hidden reaction norm.</p>
<p>At the time we made this transcriptome, we thought the identification of this bug might have been <a href="http://www.soapberrybug.org/01_cms/details.asp?ID=60"><em>Jadera hinnulea</em></a>, which is why these files are labeled <code>Jhin</code> rather than <code>Jsan</code>. (I’d rename that, but I’m afraid the contents of these files might refer to their own file names, which would cause problems. Eventually, we should just re-build the BLAST database, so eliminate that name issue.)</p>
<pre><code>/research/drangeli/BLAST_DBs/Jhae_GU_BLAST_DB/Jhae.GU.TRassembly.BLASTdb
</code></pre>
<h3 id="boisea-trivittata"><em>Boisea trivittata</em></h3>
<p>The <a href="https://upload.wikimedia.org/wikipedia/commons/4/44/Eastern_Boxelder_Bug_-_Flickr_-_treegrow.jpg">eastern box elder bug, <em>Boisea trivittata</em></a>, is the only rhopalid native to northeastern North America. Our lab created a transcriptome for this species with individuals collected in <a href="https://www.google.com/maps/place/44%C2%B033'34.6%22N+69%C2%B037'51.9%22W/">Waterville, ME</a>.</p>
<pre><code>/research/drangeli/BLAST_DBs/Btri_BLAST_database/Btri.TRassembly.BLASTdb
</code></pre>
<h3 id="other-hemiptera">Other Hemiptera</h3>
<p>The <a href="https://i5k.nal.usda.gov/">USDA i5k project</a> has a number of other genome projects in the works for Hemiptera at various stages of completion. There are currently five species with transcriptomes available, and I’ve made BLAST databases from these.</p>
<h4 id="a-note-on-taxonomy">A note on taxonomy</h4>
<p>To understand how these species might be useful, it’s helpful to have some idea of the phylogenetic relationships of these species as well as their unique features. Unfortunately, the taxonomy of true bugs is a mess. Mid-century entomologists recognised two orders: Heteroptera, the true bugs, and <a href="https://en.wikipedia.org/wiki/Homoptera">Homoptera</a>, the cicadas and their allies. However, <a href="http://science.sciencemag.org/content/346/6210/763/tab-figures-data">molecular phylogenetics</a> has found that Heteroptera is nested within what used to be ‘Homoptera’. So the term ‘Homoptera’ is now defunct, and people recognise a single order Hemiptera, with 3 suborders: <a href="https://en.wikipedia.org/wiki/Heteroptera">Heteroptera</a> (the same name with the same species in it), <a href="https://en.wikipedia.org/wiki/Auchenorrhyncha">Auchenorrhyncha</a> (cicadas, leafhoppers, treehoppers, planthoppers, and spittlebugs) and <a href="https://en.wikipedia.org/wiki/Sternorrhyncha">Sternorrhyncha</a> (aphids, whiteflies, and scale insects).</p>
<p>Here’s a <a href="https://ars.els-cdn.com/content/image/1-s2.0-S2214574517301153-gr2.jpg">figure</a> Kristen and I produced for a review we wrote on <a href="https://www.sciencedirect.com/science/article/pii/S2214574517301153">hemipteran genomics</a>. Below these species are listed in decreasing relatedness to <em>Oncopeltus</em>.</p>
<p><img src="https://ars.els-cdn.com/content/image/1-s2.0-S2214574517301153-gr2.jpg" alt="Genomeic resources for Hemiptera and their relationships"></p>
<h4 id="halyomorpha-halys"><em>Halyomorpha halys</em></h4>
<p>The invasive <a href="https://en.wikipedia.org/wiki/Brown_marmorated_stink_bug">brown marmorated stink bug</a> is a member of the <a href="https://en.wikipedia.org/wiki/Pentatomomorpha">Pentatomomorpha</a>, the infraorder that includes <em>Oncopeltus</em> (family <a href="https://en.wikipedia.org/wiki/Lygaeidae">Lygaeidae</a> and <em>Jadera</em> (family <a href="https://en.wikipedia.org/wiki/Rhopalidae">Rhopalidae</a>).</p>
<pre><code>/research/drangeli/BLAST_DBs/Hhal.CDS.BLASTdb/Hhal.BCMv0-5-3.CDS.BLASTdb
</code></pre>
<h4 id="cimex-lectularius"><em>Cimex lectularius</em></h4>
<p>The <a href="https://en.wikipedia.org/wiki/Cimex_lectularius">bedbug</a> represents the infraorder <a href="https://en.wikipedia.org/wiki/Cimicomorpha">Cimicomorpha</a>.</p>
<pre><code>/research/drangeli/BLAST_DBs/Clec.CDS.BLASTdb/Clec.OGSv1-2.CDS.BLASTdb
</code></pre>
<h4 id="gerris-buenoi"><em>Gerris buenoi</em></h4>
<p>The <a href="https://i5k.nal.usda.gov/Gerris_buenoi">water strider</a> represents the infraorder <a href="https://en.wikipedia.org/wiki/Gerromorpha">Gerromorpha</a>, the earliest diverging lineage of the Heteroptera.</p>
<pre><code>/research/drangeli/BLAST_DBs/Gbue.CDS.BLASTdb/Gbue.OGSv1-0.CDS.BLASTdb
</code></pre>
<h4 id="nilaparvata-lugens"><em>Nilaparvata lugens</em></h4>
<p>The <a href="https://en.wikipedia.org/wiki/Brown_planthopper">brown planthopper</a> is currently the only member of the <a href="https://en.wikipedia.org/wiki/Auchenorrhyncha">Auchenorrhyncha</a> with an available transcriptome.</p>
<pre><code>/research/drangeli/BLAST_DBs/Nlug.CDS.BLASTdb/Nlug.OGSv1-0.CDS.BLASTdb
</code></pre>
<h4 id="acyrthosiphon-pisum"><em>Acyrthosiphon pisum</em></h4>
<p>The <a href="https://www.hgsc.bcm.edu/arthropods/aphid-genome-project">pea pahid genome</a> was one of the first big insect genome projects. This pest represents the <a href="https://en.wikipedia.org/wiki/Sternorrhyncha">Sternorrhyncha</a>, the earliest-branching major lineage of Hemiptera.</p>
<pre><code>/research/drangeli/BLAST_DBs/Acypi.CDS.BLASTdb/Acypi.OGSv2-1b.CDS.BLASTdb
</code></pre>
<h4 id="pachypsylla-venusta"><em>Pachypsylla venusta</em></h4>
<p><a href="https://i5k.nal.usda.gov/Pachypsylla_venusta"><em>Pachypsylla venusta</em></a> is a gall-forming <a href="https://en.wikipedia.org/wiki/Jumping_plant_louse">psyllid</a>. This species represents a relatively early-branching lineage within the <a href="https://en.wikipedia.org/wiki/Sternorrhyncha">Sternorrhyncha</a>.</p>
<pre><code>/research/drangeli/BLAST_DBs/Pven.CDS.BLASTdb/Pven.BCMv0-5-3.CDS.BLASTdb
</code></pre>
<h4 id="frankliniella-occidentalis"><em>Frankliniella occidentalis</em></h4>
<p>Thrips such as <a href="https://i5k.nal.usda.gov/Frankliniella_occidentalis"><em>F. occidentalis</em></a> are members of the <a href="https://en.wikipedia.org/wiki/Phthiraptera">Phthiraptera</a>, the sister-order to the <a href="https://en.wikipedia.org/wiki/Hemiptera">Hemiptera</a>.</p>
<pre><code>/research/drangeli/BLAST_DBs/Focc.CDS.BLASTdb/Focc.BCMv0-5-3.CDS.BLASTdb
</code></pre>
<h2 id="blast-parameters">BLAST parameters</h2>
<p>The default output for local BLAST is a human-readable tabular format, give a long list of matches, including some that are very poor. However, you can adjust BLAST’s output with some additional parameters in the command line. The <a href="https://www.ncbi.nlm.nih.gov/books/NBK279684/">BLAST+ manual</a> has detailed information on all the suite’s functionality. But here’s a summary of some useful switches. These switches can be used in combination with one another.</p>
<h3 id="filter-by-e-value">Filter by E-value</h3>
<pre><code>blastn -query /path/input.filename.fa -db /path/BLASTdb \
  -evalue 1e-10 \
  &gt; output.filename
</code></pre>
<h3 id="set-a-limit-on-the-number-of-target-sequences">Set a limit on the number of target sequences</h3>
<pre><code>blastn -query /path/input.filename.fa -db /path/BLASTdb \
  -max_target_seqs 10 \
  &gt; output.filename
</code></pre>
<p>This will limit the output to the top 10 matches.</p>
<h3 id="limit-the-number-of-alignments-blast-will-return-for-each-query-subject-pair">Limit the number of alignments BLAST will return for each query-subject pair</h3>
<p>It’s possible for a query search and a subject sequence to align more of less well along different stretches. This is most relevant when the database includes very long sequences, that might have tandem duplications. This output can be reduced to show only the best such alignments. The example below will report only the best alignment between any query and subject sequence pair.</p>
<pre><code>blastn -query /path/input.filename.fa -db /path/BLASTdb \
  -max_hsps 1 \
  &gt; output.filename
</code></pre>
<h3 id="run-blast-using-multiple-processors">Run BLAST using multiple processors</h3>
<p><strong>nscc</strong> is a multi-processor computing cluster. By default, most programs will use only one processor, but you can direct many of them to “multi-thread” and use multiple processors simultaneously.</p>
<p>Do this only with caution, since it will impact other users on <strong>nscc</strong>. As a rule, you should only use multi-threading on node 26. The biology node has 32 processors, and as a courtesy to other users, it’s good form to use at most half of those at any time. The example below uses 16 processors.</p>
<pre><code>blastn -query /path/input.filename.fa -db /path/BLASTdb \
  -num_threads 16 \
  &gt; output.filename
</code></pre>
<h3 id="change-the-output-format">Change the output format</h3>
<p>BLAST has the ability to render its output in format other than the default table and alignment. Several options are possible, and they’re described in Table C1 in the Appendix to the <a href="https://www.ncbi.nlm.nih.gov/books/NBK279684/">BLAST+ manual</a>.  If you look at this table, scroll down or search for the <code>outfmt</code> entry.</p>
<p>For many big data bioinformatics approaches, it can be useful to get your BLAST output in a TSV format that can be imported into R or other applications.  One line per result is produced with  <code>-outfmt 6</code>. But you’ll want to specify exactly which metadata the BLAST returns. They are specified in double quotes, as in the example below.</p>
<pre><code>blastn -query /path/input.filename.fa -db /path/BLASTdb \
  -evalue 1e-10 -max_target_seqs 10 -max_hsps 1 -num_threads 16 \
  -outfmt "6 qseqid sseqid pident qlen length mismatch evalue bitscore" \
  &gt; output.filename
</code></pre>
<hr>
<p>-<em>Dave Angelini</em>, 2018</p>

