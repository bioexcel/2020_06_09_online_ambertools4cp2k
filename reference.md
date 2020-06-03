---
layout: reference
---

***

## AmberTools and Amber links for Quick Reference

*   For more information on [AmberTools](http://ambermd.org/AmberTools.php) look into its main page. 
*   Amber and Ambertools documentation can be found [here](http://ambermd.org/MailingLists.php).
    * `parmed` documentation: http://parmed.github.io/ParmEd/html/index.html
    * `cpptraj` documentation: https://amber-md.github.io/cpptraj/CPPTRAJ.xhtml
*   Amber has developed many tutorials that can be helpful to your simulations. Please check [AmberMD tutorials](http://ambermd.org/tutorials/) webpage for more information on the system set up. We found specially helpful: 
    * [Fundamentals of LEap](http://ambermd.org/tutorials/pengfei/index.php).
    * [An Introduction to Molecular Dynamics Simulations using AMBER](http://ambermd.org/tutorials/basic/tutorial0/index.htm)
    * [Simulating a small fragment of DNA](http://ambermd.org/tutorials/basic/tutorial1/index.htm)
    * [Changing Protonation State with PDB2PQR and reading AMBER FF residue names (6IYC)](http://www.charmm-gui.org/?doc=demo&id=amber_ff&lesson=3)
    * [Creating Special Systems for Molecular Simulations](http://ambermd.org/tutorials/AdvancedSetup.php)
    * [Extending the Amber Force Field](http://ambermd.org/tutorials/ForceField.php)
*   Amber community is usually receptive and helpful if you have a problem. Do not hesitate to use the [Amber Mailing lists](http://ambermd.org/MailingLists.php).
*   More information of [Amber forcefields](https://ambermd.org/AmberModels.php).


## CP2K links for Quick Reference 

*   For more information on [CP2K](https://www.cp2k.org) look into its webpage.
*   CP2K documentation can be found [here](https://manual.cp2k.org/#gsc.tab=0)
*   [CP2K tutorials](https://www.cp2k.org/howto).

***

## Glossary

{:auto_ids}
changeset
:   A group of changes to one or more files that are or will be added
    to a single [commit](#commit) in a [version control](#version-control)
    [repository](#repository).

commit
:   To record the current state of a set of files (a [changeset](#changeset))
    in a [version control](#version-control) [repository](#repository). As a noun,
    the result of committing, i.e. a recorded changeset in a repository.
    If a commit contains changes to multiple files,
    all of the changes are recorded together.

conflict
:   A change made by one user of a [version control system](#version-control)
    that is incompatible with changes made by other users.
    Helping users [resolve](#resolve) conflicts
    is one of version control's major tasks.

HTTP
:   The Hypertext Transfer [Protocol](#protocol) used for sharing web pages and other data
    on the World Wide Web.

merge
:   (a repository): To reconcile two sets of changes to a
    [repository](#repository).

protocol
:   A set of rules that define how one computer communicates with another.
    Common protocols on the Internet include [HTTP](#http) and [SSH](#ssh).

remote
:   (of a repository) A version control [repository](#repository) connected to another,
    in such way that both can be kept in sync exchanging [commits](#commit).

repository
:   A storage area where a [version control](#version-control) system
    stores the full history of [commits](#commit) of a project and information
    about who changed what, when.

resolve
:   To eliminate the [conflicts](#conflict) between two or more incompatible changes to a file or set of files
    being managed by a [version control](#version-control) system.

revision
:   A synonym for [commit](#commit).

SHA-1
:   [SHA-1 hashes](https://en.wikipedia.org/wiki/SHA-1) is what Git uses to compute identifiers, including for commits.
    To compute these, Git uses not only the actual change of a commit, but also its metadata (such as date, author,
    message), including the identifiers of all commits of preceding changes. This makes Git commit IDs virtually unique.
    I.e., the likelihood that two commits made independently, even of the same change, receive the same ID is exceedingly
    small.

SSH
:   The Secure Shell [protocol](#protocol) used for secure communication between computers.

timestamp
:   A record of when a particular event occurred.

version control
:   A tool for managing changes to a set of files.
    Each set of changes creates a new [commit](#commit) of the files;
    the version control system allows users to recover old commits reliably,
    and helps manage conflicting changes made by different users.
