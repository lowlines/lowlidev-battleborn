(Bug report following the UPR’s failed evacuation of the Aviant system, Menneck-B)

Project Scepter / SCEPTER-10048963
[Magnus][UPR][Field Operations] – MRBX 00419.c7, “Mephis”, behaves inconsistently during Varelsi mass-teleportation

Details ----------
Type: Bug Assignee: [Gunnar Kleese]
Priority: P3 Reporter: [User Testing]
Status: Resolved, Needs More Information Watcher: [Elandra Saint-Wu]
Components: Magnus AI, Varelsi Research
Severity: B Normal
User Path: Rare
Observed Results ----------
We’ve received numerous complaints regarding the recent performance of Mephis, the onboard Magnus of the UPR exo-station “The Wiseman”.

Users indicate that while attempting evacuation of the Aviants from the Menneck-B system, Mephis was initially functioning as intended, coordinating the fleet and directing all comms, targeting, and navigation data using The Wiseman’s array. However, during a Varelsi mass-teleportation sequence, Mephis exhibited aberrant behavior, sending communications with non-standard encryptions, disabling auto-targeting systems, and routing a capital ship directly into The Wiseman, which drifted into the gravity well of Sau Nona and crashed.

As a result, users report less than .3% of the population was evacuated from inhabited worlds in the system (Itka, Sau Nona, Madan, Stragi, and Ezun, Stragi’s largest moon). Additionally, a large number of transports were reported missing.

The black box of The Wiseman is unrecovered, but data indicates it was intact at the time of impact. We’ve tested data recorder integrity under Dark-like conditions and it should remain stable for approximately 20 years.
Due to the inconsistent functionality of Mephis at the time of impact, it is difficult to determine to severity of damage the Magnus sustained, if any.

Steps to Reproduce ----------
1. Initialize MRBX 00419.c7, “Mephis”, networked to an appropriate vessel
2. Navigate the vessel in proximity to an ongoing Varelsi mass-teleportation sequence
3. Observe that Mephis behaves inconsistently

Expected Behavior ----------
Magnus AI should maintain standard functionality under all operating conditions.

Build Info ----------
Platform: Super-capital exo-station, model UPR654-7[m], “The Wiseman”
Changelist: 1
Reproduction Rate: 1/1

Attachments ----------
UPRuserlog.txt; MadanEvacTransportComms.mp9; saunona_surface.vid

Comments ----------
[Bertram Hastings] added a comment - 5 days ago
///How many users are reporting similar issues? Is this an isolated case?

_[Elandra Saint-Wu] replied - 5 days ago
///So far, this is the only reported case, but this single incident was reported over 200 times, mostly UPR officers and other premium users involved in the evacuation. Also, , please update the bug description to include the established term “portal bloom” for searchability.

[Bertram Hastings] replied - 5 days ago
///... okayyy, can we get a sample of this non-standard encryption? Might be able to back-engineer some of the issue if my team can see these effects. Also, who shot that surface footage? Pinging .

[Elandra Saint-Wu] replied - 5 days ago
///I’ve attached an audio log sifted from a data packet burst on the emergency channels during the issue. Unfortunately, since Mephis wasn’t parsing traffic correctly, virtually all channels’ signal-to-noise was shot to hell. As for the surface footage, judging from the low viewing angle and resolution, this was a personal recorder held by a Finisci; this would also account for the shaking, if it was held by flippers instead of hands.

[Morton Barrett] added a comment - 4 days ago
///The audio log is actually two layers, one from an organic source, probably a female Buteonen judging from vocal signatures, and the other synthesized. So far, I’ve only been able to decrypt the word “Augustus” and a fragment of coordinates, presumably from the onboard navigation system. If we can recover either that transport or, better yet, Mephis himself, I can get a much better look at this issue.

[Gunnar Kleese] added a comment - 2 days ago
///Yes, yes, this is all well and fine, but what good is this information with that dismal reproduction rate? 1/1, really? Can we get QA on this?

[Elandra Saint-Wu] replied - 2 days ago
/// We would need a Magnus fresh off the line as well as a few hundred thousand tons of UPR materiel to house it in. Then we’d have to navigate it directly into the path of a Varelsi portal sequence during the brief window while it’s active.

[Gunnar Kleese] replied - 1 day ago
/// Thank you for providing ME the details of how to do YOUR job. It’s clear you know how to proceed, you know where to find me when you’re done. Resolving NMI (Needs More Information).