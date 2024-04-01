---
date: 2024-03-26
title: "Peeling the SecOps Onion"
linkTitle: "Peeling the SecOps Onion"
author: Sacha Wharton
---




<div class="col-center">
<img src="/images/peelingonion.png" alt="peeling the onion" height="419px" width="935px" />
</div>
<p></p>

## Exposing Vulnerabilities by Peeling the SecOps Onion

How do you peel an onion? Normally, you would peel an onion layer by layer and that's precisely what Ortelius can do for you minus the crying bit. The security landscape is treacherous. We have witnessed all types of, software supply chain, malware and ransomware attacks from maliciously abusing individuals and organizations for selfish gain. These attacks are not going to stop anytime soon. Software developers must start peeling the onion and exposing what potentially problematic code they are using to deliver safe software to end users. 

In order to protect the software we deliver, we need to ask "Do you know what packages and dependencies your applications are using?" Do you even need all those packages or dependencies? How do we know what to report on? Well lets breakdown some areas where Ortelius can help you peel this without any tears. In this example, I will use Dev Containers, my particular area of interest and expertise. 

Since there is a strong push towards Platform Engineering a Platform Team can provide approved CISO/SecOps development containers with all the tools, packages and dependencies needed to develop that specific application. Whilst Dev Containers are nothing new, they allow engineers to get systems up and running very quickly with minimal energy being expounded in the setup process. This cam be especially helpful for new joiners to the team, open-source contributors or commercial coders. Access to these Dev Containers can be isolated with minimal communication links, securely configured and made highly available with the use of Kubernetes. Combine Kubernetes with one of my absolute favorite tools [DevPod](https://devpod.sh/) from Loft Labs and you have a super powerful solution in making this a reality.

Now this is where Ortelius comes in. Ortelius is like the black box of a commercial jet. Ortelius consumes and stores every piece of information generated by the DevSecOps process, with versions for historical trend analysis. With the use of powerful dashboarding, search and reporting capabilities, Ortelius will reveal every inch of your Dev Container universe and give you the power to make quick decisions, remediations or alert Platform Teams to dangerously vulnerable packages and dependencies. So the next time your Team gets asked "Do you know what ingredients are baked into your container cake?" you can answer with hardcore reporting from the Ortelius security intelligence dashboard, giving your leaders and teammates the reassurance they require. 

When you peel the onion with Ortelius, you can provide the following:
- Attestation/Provenance
- Open-Source Dependencies
- Licensing
- Vulnerabilities based on versions
- Configuration including deployment metadata
- Federate SBOM Reporting in decoupled architectures
- SBOM sharing across teams
- Available ingredients
- Exposure and impact of vulnerabilities across the enterprise
- Zero Trust Data
- Open-source Inventory
- Historical Trends


## Conclusion
With Ortelius firmly cemented in gathering your DevSecOps intelligence, your environment you can take the blind folds off your application universe and root out the so called weeds and ensure you have the safest possible environment at your disposal. I wish you safe computing and minimal tears as you peel away the layers of the onion.


{{< blocks/section color=white >}}

<h2 class="text-left">Meet the Author</h2>
<hr>

{{< blocks/feature_dual >}}

Learn More About:
- [Sacha Wharton](https://www.linkedin.com/in/sachawharton/)

{{< /blocks/feature_dual >}}
{{< blocks/feature_dual >}}

<div style="position:relative;left:-60%">
<img src="/images/sacha.jpg" alt="Sachawharton" height="400px" width="400px" />
</div>

{{< /blocks/feature_dual >}}
{{< /blocks/section >}}