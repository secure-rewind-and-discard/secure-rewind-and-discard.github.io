---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
<h2> Welcome to the <b>Secure Rewind and Discard Project </b> Website! You can find three published papers and their artifact code here.</h2>


->  <a href="#rewind_discard">Rewind & Discard: Improving Software Resilience using Isolated Domains <img src="./files/click_finger_touch_icon.png" width="30" height="30" alt="Go to Rewind & Discard" /></a>

-> <a href="#environmental">Exploring the Environmental Benefits of In-Process Isolation for Software Resilience <img src="./files/click_finger_touch_icon.png" width="30" height="30" alt="Go to Rewind & Discard" /></a>

->  <a href="#sdradffi">Friend or Foe Inside? Exploring In-Process Isolation to Maintain Memory Safety for Unsafe Rust <img src="./files/click_finger_touch_icon.png" width="30" height="30" alt="Go to Rewind & Discard" /></a>



---------------------------------------------------------------------------------
<h2><b> Publications </b></h2>  
---------------------------------------------------------------------------------

<h2 id="rewind_discard"> Rewind & Discard: Improving Software Resilience using Isolated Domains (2023)</h2>  
*Merve Gülmez*,
*Thomas Nyman*,
*Christoph Baumann*,
*Jan Tobias Mühlberg*

[DOI:10.1109/DSN58367.2023.00046](http://doi.org/10.1109/DSN58367.2023.00046) (accepted at IEEE DSN'23)

Open Access : [<img src="./files/pdf.icon.png" width="30" height="30"/>](./files/2023_sdrad.pdf)


Extended Version: [arXiv:1905.10242 \[cs.CR\]](https://arxiv.org/pdf/2205.03205.pdf) [<img src="./files/slides.icon.png" width="30" height="30"/>](./files/Gulmez_DSN_2023_Research_Track.pptx)

***Abstract***
> Well-known defenses exist to detect and mitigate common faults and memory safety vulnerabilities in software.  Yet, many of these mitigations do not address the
challenge of software _resilience_ and _availability_, i.e., whether a
system can continue to carry out its function and remain responsive, while being under attack and subjected to malicious inputs. We propose _secure rewind and discard of isolated domains_ as an efficient and secure method of improving the resilience of software that is targeted by run-time attacks.  In difference to established approaches, we rely on
compartmentalization instead of replication and checkpointing.  We show the practicability of our methodology by realizing a software library for
Secure Domain Rewind and Discard SDRaD and demonstrate how SDRaD can be applied to real-world software.

<button id="toggleButton" onclick="toggleBibTeX('entry1')">Show BibTeX</button>
<div id="entry1" class="bibtex">
<pre>
@inproceedings{Gulmez23a,
  author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and 
            Mühlberg, Jan Tobias},
  title = {Rewind \& Discard: Improving Software Resilience Using Isolated Domains},
  booktitle = {Proceedings of 53rd Annual IEEE/IFIP International Conference on  
               Dependable Systems and Networks},
  series = {DSN '23},
  month = {jun},
  year = {2023},
  pages = {402--416},
  issn = {2158-3927},
  url = {http://doi.org/10.1109/DSN58367.2023.00046}, 
  doi = {10.1109/DSN58367.2023.00046},
  location = {Porto, Portugal},
  publisher = {IEEE Computer Society},
  address = {Washington, DC, USA},
}

@misc{Gulmez22,
  author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and 
            Mühlberg, Jan Tobias},
  title = {Unlimited Lives: Secure In-Process Rollback with Isolated Domains},
  year = {2022},  
  doi = {10.48550/ARXIV.2205.03205},  
  howpublished = {\tt arXiv:2205.03205 [cs.CR]}, 
  url = {https://arxiv.org/abs/2205.03205},
}
</pre>
</div>


***Source Code***

Source code for the SDRaD implementation is available at [EricssonResearch /
secure-rewind-and-discard](https://github.com/secure-rewind-and-discard)


<h2 id="environmental">Exploring the Environmental Benefits of In-Process Isolation for Software Resilience(2023)</h2>
*Merve Gülmez*,
*Thomas Nyman*,
*Christoph Baumann*,
*Jan Tobias Mühlberg*

[DOI:10.1109/DSN-S58398.2023.00056](http://doi.org/10.1109/DSN-S58398.2023.00056) (accepted at IEEE DSN'23)

[arXiv:2306.02131 \[cs.CR\]](https://arxiv.org/pdf/2306.02131.pdf)        [<img src="./files/slides.icon.png" width="30" height="30"/>](./files/Gulmez_DSN_2023_Doctoral_Forum.pdf)



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
@inproceedings{Gulmez23b,
  author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and 
            Mühlberg, Jan Tobias},
  title = {Exploring the Environmental Benefits of In-Process Isolation for 
           Software Resilience},
  booktitle = {Proceedings of 53rd Annual IEEE/IFIP International Conference on 
               Dependable Systems and Networks - Supplemental Volume (DSN-S)},
  series = {DSN '23},
  month = {jun},
  year = {2023},
  pages = {203--205},
  issn = {2833-292X/23},
  url = {http://doi.org/10.1109/DSN-S58398.2023.00056},
  doi = {10.1109/DSN-S58398.2023.00056},
  location = {Porto, Portugal},
  publisher = {IEEE Computer Society},
  address = {Washington, DC, USA},
}
@misc{Gulmez23c,
  author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and 
            Mühlberg, Jan Tobias},
  title = {Exploring the Environmental Benefits of In-Process Isolation for 
           Software Resilience},     
  year = {2023}, doi = {10.48550/ARXIV.2306.02131},
  howpublished = {\tt arXiv:2306.02131 [cs.CR]},
  url = {https://arxiv.org/abs/2306.02131},
}
</pre>
}
</div>


<h2 id="sdradffi"> Friend or Foe Inside? Exploring In-Process Isolation
to Maintain Memory Safety for Unsafe Rust (2023) </h2>
*Merve Gülmez*,
*Thomas Nyman*,
*Christoph Baumann*,
*Jan Tobias Mühlberg*,

[DOI:10.1109/SecDev56634.2023.00020](http://doi.org/10.1109/SecDev56634.2023.00020) (accepted at IEEE SecDev 23) 

FOSDEM Talk : [<img src="./files/video_icon.png" width="30" height="30"/>](https://fosdem.org/2024/schedule/event/fosdem-2024-2632-friend-or-foe-inside-exploring-in-process-isolation-to-maintain-memory-safety-for-unsafe-rust/)

Open Access : [<img src="./files/pdf.icon.png" width="30" height="30"/>](./files/2023_sdrad_ffi.pdf)

Extended Version: [arXiv:2306.08127 \[cs.CR\]](https://arxiv.org/pdf/2306.08127.pdf)  [<img src="./files/slides.icon.png" width="30" height="30"/>](./files/Gulmez_IEEESecDev_2023.pptx)


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

@INPROCEEDINGS{Gulmez23d,
  author={Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and Mühlberg, Jan Tobias},
  booktitle={2023 IEEE Secure Development Conference (SecDev)}, 
  title={Friend or Foe Inside? Exploring In-Process Isolation to Maintain Memory Safety for Unsafe Rust}, 
  year={2023},
  volume={},
  number={},
  pages={54-66},
  doi={10.1109/SecDev56634.2023.00020}
}


@misc{Gulmez23c,
  author = {Gülmez, Merve and Nyman, Thomas and Baumann, Christoph and 
            Mühlberg, Jan Tobias},
  title = {Friend or Foe Inside? Exploring In-Process Isolation to 
           Maintain Memory Safety for Unsafe Rust}, 
  year = {2023}, 
  doi = {10.48550/ARXIV.2306.08127},
  howpublished = {\tt arXiv:2306.08127 [cs.CR]},
  url = {https://arxiv.org/abs/2306.08127},
}
</pre>
</div>

***Source Code***

Source code for the sdradrustffi implementation is available at [secure-rewind-and-discard](https://github.com/secure-rewind-and-discard)



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



