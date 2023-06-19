---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<h2>Rewind & Discard: Improving Software Resilience using Isolated Domains (2023)</h2>  
*Merve Gülmez*,
*Thomas Nyman*,
*Christoph Baumann*,
*Jan Tobias Müehlberg*,
[arXiv:1905.10242 \[cs.CR\]](https://arxiv.org/pdf/2205.03205.pdf)  
(accepted at IEEE DSN'23)

***Abstract***
> Well-known defenses exist to detect and mitigate common faults and memory safety vulnerabilities in software.  Yet, many of these mitigations do not address the
challenge of software _resilience_ and _availability_, i.e., whether a
system can continue to carry out its function and remain responsive, while being under attack and subjected to malicious inputs. We propose _secure rewind and discard of isolated domains_ as an efficient and secure method of improving the resilience of software that is targeted by run-time attacks.  In difference to established approaches, we rely on
compartmentalization instead of replication and checkpointing.  We show the practicability of our methodology by realizing a software library for
Secure Domain Rewind and Discard SDRaD and demonstrate how SDRaD can be applied to real-world software.

<button id="toggleButton" onclick="toggleBibTeX('entry1')">Show BibTeX</button>
<div id="entry1" class="bibtex">
<pre>
@misc{Gulmez23,
    author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and Mühlberg, Jan Tobias},
    title = {Rewind \& Discard: Improving Software Resilience Using Isolated Domains},
    year = {2023},  
    howpublished = {To appear in 53rd Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN 2023)}, 
    note = {A technical report is available at \url{https://arxiv.org/pdf/2205.03205.pdf}}
}
</pre>
</div>


***Source Code***

Source code for the SDRaD implementation is available at [EricssonResearch /
secure-rewind-and-discard](https://github.com/EricssonResearch/secure-rewind-and-discard/))


<h2>Exploring the Environmental Benefits of In-Process Isolation for Software Resilience(2023)</h2>
*Merve Gülmez*,
*Thomas Nyman*,
*Christoph Baumann*,
*Jan Tobias Müehlberg*,
[arXiv:2306.02131 \[cs.CR\]](2306.02131)  
(accepted at IEEE DSN'23)

***Abstract***

> Memory-related errors remain an important cause
of software vulnerabilities. While mitigation techniques such as
using memory-safe languages are promising solutions, these do
not address software resilience and availability. In this paper,
we propose a solution to build resilience against memory attacks
into software, which contributes to environmental sustainability
and security.


<button id="toggleButton" onclick="toggleBibTeX('entry2')">Show BibTeX</button>
<div id="entry2" class="bibtex">
<pre>
@misc{Gulmez23,
    author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and Mühlberg, Jan Tobias},
    title = {Exploring the Environmental Benefits of In-Process Isolation for Software Resilience},
    year = {2023},  
    howpublished = {To appear in 53rd Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN 2023)}, 
    note = {A technical report is available at \url{https://arxiv.org/pdf/2306.02131.pdf}}
</pre>
}
</div>



<style type="text/css">
  .bibtex {
    display: none;
  }
</style>
<script>
    function toggleBibTeX(entryId) {
        var bibtexDiv = document.getElementById(entryId);
        var toggleButton = document.getElementById("toggleButton-" + entryId);

        if (bibtexDiv.style.display !== "block") {
            bibtexDiv.style.display = "block";
            toggleButton.innerHTML = "Hide BibTeX";
        } else {
            bibtexDiv.style.display = "none";
            toggleButton.innerHTML = "Show BibTeX";
        }
    }
</script>



