# .github
A Brainwriting about the Solid Project according to own experience
----
codebase is at github
the coreteam is just a bunch of folks
the community is endless
it’ s about linked data expressed in turtle or rdf
authing is essential for the functionality of the system
fine granulated access control is managed with the help of access control lists which are stored in .acl-files
they seem to be some kind of meta- or extended data attached to files in the storage system, which is apart from the unique identity management the second main functionality of a pod
pod is personal online datastore
timbl is the father of the system as everyone can imagine easily
different layers need to be examined
http is definitely standardized
a common used linguistic structure would look like follows (called a quad)
subject predicate object why
where the first three have certain rules to be applied and the fourth would be the socalled graph
the semantic web as a whole would be called giant global graph
no one knows if this thing really exists
the subject would be the thing to be examined and is probably just a word (could be a string)
the predicate is an URI which means it’ s part of a certain vocabulary and worldwide unique
the object MAY be an URI or a literal (that means either a string or a number)
the graph would be the returned SOMETHING and can be considered as the answer to the query
rules to the concatination of the four things MUST be applied
so a quad can be considered as a literally linguistic semantic structure
NSS (Node Solid Server) is written in javascript and running under node/npm
the actual version (february 2020) is 5.2.3
a databrowser is running as standard app and displays the storage system and gives main exploration possibilities
the user is enabled to create a webid, which is a unique URI holding the card (this can be thought of as the profile)
the solid-compliant applications read and write from and to the POD and the user has autonomous control over the data (and naturally owns it)
the authentication is done openid-way (OIDC) (v0.8 or v1.0)
ONE aim of the project is to make multiple logins across multiple apps obsolete because you have total control over the stored data and can assign the apps the minimum possible access-rights
the user should be able to move his data across multiple PODs
one user can have multiple webids hold at multiple identity providers
best case is different apps are enabled to talk to each other
control is shifted from the serverside to the clientside
the system can be installed locally via npm at localhost, but if you want a POD-server a root-server would make the most sense of it
the contacts are managed by the foaf-logic (Friend of a Friend)
a whole new ecosystem evolves
the specification should be understood as work-in-progress
as of easter 2020 we have 5-6 discovered public pod-servers
in 2021 SolidOS gets in the focus
as of summer 2021 we have five pod providers that seem reliable
all efforts are being strengthened, public convincing of the concept as well as the technical side
in late 2021 the community solid server has a working 1.1.0 version and adds functionality to the family of the ecosystem
but the whole solidverse is a long term project and still in an early phase
see, much app development is done
the core system is mashlib which is called a databrowser otherwise
at the eve of 2022 the public recognition of the system grows slowly but steadily
we have solid world - which is our global showcase - regularly
node solid server and community solid server coexist and are both technically functional
fine granulated access rights are heavily worked on
the solidverse, as we call it, stands healthy and wealthy on two legs and our crew is growing
the pandemic can’t prevent us from developing and testing
but still there’s more to discover and to learn than we ever dreamt of
our aim is to flip the web right side up
on the long term we can only win
the system should be useful immediately and understandable intuitively
still the UX can be admittedly improved
well, we may still be in an early stage but we approach production
as of spring 2022 the community solid server gets in an focused position
it’s the backend, mashlib is the frontend
mashlib is the library, solidos makes use of
lots of diminuitive drops form an ocean
