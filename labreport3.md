# Lab Report 3 - Researching Commands
---
*Today we will focus on:*
```
- The less command 
``` 
---
Some command line options for less include:
- `-N`
- `-`
- `-`
- `-`

---
**1. `less -N`**

**Command: `less -N ./technical/plos/pmed.0020281.txt`**

- Output:
  ```
  1 
      2   
      3     
      4       
      5         
      6         Whistleblowers serve no function if they cannot tell their stories. The present story of
      7         whistleblowing—as discussed, in part, in 
      8         PLoS Medicine —that involves the pharmaceutical industry, pharmaceutical
      9         benefit management corporations, the managed care industry, and the political and lobbying
     10         forces that zealously guard their secrets could not have been told without the help of
     11         courageous men and women [1, 2] For that reason, those of us who congregated in Washington,
     12         D.C., on May 15th, 2005, at the invitation and support of the Public Library of Science and
     13         the Government Accountability Project feel particularly humbled and grateful to these two
     14         sponsors. Our convictions could not have been aired were it not for the essential First
     15         Amendment work of responsible journalists, who exemplify the best in investigatory
     16         research.
     17         For me, whistleblowing is not a theoretical exercise. It has a human face and tangible
     18         features. It is the face of children and adults who have been injured or killed by
     19         misrepresented pharmaceuticals; clinical research trial results that have been sequestered
     20         from the scientific community and whose incomplete findings cause injury; and
     21         pharmaceuticals that are detailed to physicians, not to save lives or necessarily improve
     22         the health or welfare of the recipients, but to make money.
     23         In the lonely and, at times, discouraging world of whistleblowing, we whistleblowers are
     24         passionate, and often successful, because our efforts have a different goal than the
     25         corporations and political interests whose operations we occasionally challenge. Our goal
     26         is to tell the truth. That honest effort is the source of any ethical difference we can or
     27         might make. Truth is the basis for the power of a whistleblower, one that can withstand the
     28         assault of unprecedented odds against being heard put forth by that sum of political power,
     29         expediency, and money.
     30         A whistleblower's success depends upon competent and articulate media. The debate to
     31         improve the status quo—be it in pharmaceutical marketing or managed-care decision
     32         making—cannot proceed or flourish without it.
     33         Ralph Waldo Emerson, American essayist and philosopher (1803–1882), commented about
     34         success (I have adapted his comments for all of us who gathered in Washington in mid-May
     35         2005): “To leave the world a bit better, whether by a healthy child, a garden patch or a
     36         redeemed social condition; to know even one life breathed easier because you have lived;
     37         this is to have succeeded [as a whistleblower].”
     38       
     39     
     40   
  ```


**Command: `grep -n "Genome" ./technical/plos/*`**

- Output:
  ```
  ./technical/plos/journal.pbio.0020052.txt:126:        Genome Project. The proponents of such models point to the success of GNU/Linux in the
  ./technical/plos/journal.pbio.0020068.txt:64:        Endosymbiont Genomes: Spanning the Gamut from Static to Plastic
  ./technical/plos/journal.pbio.0020068.txt:137:        between a free-living lifestyle and obligate endosymbiosis. Genome-level data from these
  ./technical/plos/journal.pbio.0020145.txt:131:        www.bio.davidson.edu/people/macampbell/Hope/DQ/DQ10.html). First-year students use Genome
  ./technical/plos/journal.pbio.0020161.txt:36:        Trust's Genome Campus at Hinxton, near Cambridge, United Kingdom. ‘The French and Germans
  ./technical/plos/journal.pbio.0020206.txt:83:        Genome duplication events generate a duplicate for every gene in the genome,
  ./technical/plos/journal.pbio.0020213.txt:102:        Department of Energy's Joint Genome Project based in Walnut Creek, California. The focus
  ./technical/plos/journal.pbio.0020232.txt:193:        The Mouse Genome Informatics (http://www.informatics.jax.org/) accession numbers of the
  ./technical/plos/journal.pbio.0020241.txt:41:        (Mouse Genome Sequencing Consortium 2002).
  ./technical/plos/journal.pbio.0020306.txt:106:        United States Department of the Environment's Joint Genome Initiative (JGI) at Walnut
  ./technical/plos/journal.pbio.0030024.txt:9:        Although genetic information exploded out of the Human Genome Project, it has been of
  ./technical/plos/journal.pbio.0030024.txt:101:        adds, it's a much richer dataset than the Human Genome Project. “As we're ramping up—fully
  ./technical/plos/journal.pbio.0030024.txt:143:        limitations. Much like the Human Genome Project, the information will be the starting point
  ./technical/plos/journal.pbio.0030065.txt:80:        term lists come from the Human Genome Organization (www.gene.ucl.ac.uk/hugo; 20,000 gene
  ./technical/plos/pmed.0010058.txt:58:        recent completion of the Human Genome Project suggests that the genetics of diabetes may
  ./technical/plos/pmed.0020212.txt:60:        Genomewide Linkage Studies of Schizophrenia
  ./technical/plos/pmed.0020278.txt:29:        applicable to humans. The Human Genome Project [5] tells us that there is sufficient
  ```
  
**Explanation:**

- The `-n` option for grep gives you the line number inside the text file that contains the word that you are looking for. So in this case we were looking for Precipitated in biomed and Genome in plos.

**Citation:**
- https://man7.org/linux/man-pages/man1/grep.1.html

---
**1. `-grep -n`**

**Command: ` `**

- Output:
  ```
  
  ```


**Command: ` `**

- Output:
  ```
  
  ```
  
**Explanation:**

- 

**Citation:**

- 
