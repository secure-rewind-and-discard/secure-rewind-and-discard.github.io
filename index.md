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
@misc{Gulmez23a,
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
[arXiv:2306.02131 \[cs.CR\]](https://arxiv.org/pdf/2306.02131.pdf)  
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
@misc{Gulmez23b,
    author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and Mühlberg, Jan Tobias},
    title = {Exploring the Environmental Benefits of In-Process Isolation for Software Resilience},
    year = {2023},  
    howpublished = {To appear in 53rd Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN 2023)}, 
    note = {A technical report is available at \url{https://arxiv.org/pdf/2306.02131.pdf}}
</pre>
}
</div>


<h2>Friend or Foe Inside? Exploring In-Process Isolation
to Maintain Memory Safety for Unsafe Rust (2023) </h2>
*Merve Gülmez*,
*Thomas Nyman*,
*Christoph Baumann*,
*Jan Tobias Müehlberg*,
[arXiv:2306.08127 \[cs.CR\]](https://arxiv.org/pdf/2306.08127.pdf)  

***Abstract***

> Rust is a popular memory-safe systems programming
language. In order to interact with hardware or call into non-
Rust libraries, Rust provides unsafe language features that shift
responsibility for ensuring memory safety to the developer. Failing
to do so, may lead to memory safety violations in unsafe code
which can violate safety of the entire application. In this work
we explore in-process isolation with Memory Protection Keys
as a mechanism to shield safe program sections from safety
violations that may happen in unsafe sections. Our approach is
easy to use and comprehensive as it prevents heap and stack-
based violations. We further compare process-based and in-process
isolation mechanisms and the necessary requirements for data
serialization, communication, and context switching. Our results
show that in-process isolation can be effective and efficient, permits
for a high degree of automation, and also enables a notion of
application rewinding where the safe program section may detect
and safely handle violations in unsafe code.

<button id="toggleButton" onclick="toggleBibTeX('entry3')">Show BibTeX</button>
<div id="entry3" class="bibtex">
<pre>
@misc{Gulmez22c,
  author = {Gülmez, Merve and Nyman, Thomas and Bauman, Christoph and 
            Mühlberg, Jan Tobias},
  title = {Friend or Foe Inside? Exploring In-Process Isolation to 
           Maintain Memory Safety for Unsafe Rust}, 
  year = {2023}, 
  doi = {10.48550/ARXIV.2306.08127},
  howpublished = {{\tt arXiv:2306.08127 [cs.CR]}},
  url = {https://arxiv.org/abs/2306.08127},
}
</pre>
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



