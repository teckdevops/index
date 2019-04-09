---
layout: post
title: AWS EC2 - Management Console
---

<div dir="ltr" style="text-align: left;" trbidi="on">
<div class="separator" style="clear: both; text-align: center;">
</div>
<div class="separator" style="clear: both; text-align: center;">
</div>
<h2 style="text-align: left;">
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">AWS EC2 - Management Console</span></h2>
<div style="text-align: left;">
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">A Blog post to explain the basic concepts of AWS EC2(Amazon Web Service Elastic </span><span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">Compute Cloud) service.</span>&nbsp;</div>
<div style="text-align: left;">
<div style="text-align: justify;">
<br /></div>
</div>
<div style="text-align: justify;">
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">AWS EC2 is a service that basically provides scalable compute capacity on an on-demand, pay-per-use basis to its end users. EC2 is simply based on server virtualization which provides unlimited set of machines with of almost unlimited capacity. As a AWS EC2 users we generally call these machines as an "instance".</span></div>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"></span><br />
<div>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><br /></span></span></div>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">
Users can dynamically create,work,expand and shutdown EC2 instances as per use and as per requirement.</span><br />
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><br /></span>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">Under this blog we will explore how user can create an instances via AWS graphical user interface(GUI). Please follow AWS EC2 CLI to perform same set of process via Command line interface(CLI). So, no more talks let's get started!!!</span><br />
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11pt;">** Prerequisite:</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11pt;"><br /></span><span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11pt;">- AWS Console Access i.e. A valid account on AWS Portal.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11pt;">- A Valid user with permission of creation and deletion of AWS EC2 Instances.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11pt;"><br /></span>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"></span>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><u><b>AWS - Working with EC2 instance via GUI</b></u></span><br />
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><u><b><br /></b></u></span>
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;">Please follow below steps to start an EC2 instance via AWS Management Console</span><br />
<span style="font-family: &quot;trebuchet ms&quot; , sans-serif;"><b><u><br /></u></b></span>
<br />
<div style="text-align: left;">
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">1. &nbsp;Login to AWS Management Console&nbsp;</span></div>
<div style="text-align: left;">
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Login to AWS Management console and select EC2 from available services.&nbsp;</span></div>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://3.bp.blogspot.com/-0I603-aAXOo/WZgq5NFIxwI/AAAAAAAACHg/_-r-PB8rDJkUF25RMbiQY2FlJF2StirIACLcBGAs/s1600/1.%2BSelect%2BEC2.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="330" data-original-width="513" height="205" src="https://3.bp.blogspot.com/-0I603-aAXOo/WZgq5NFIxwI/AAAAAAAACHg/_-r-PB8rDJkUF25RMbiQY2FlJF2StirIACLcBGAs/s320/1.%2BSelect%2BEC2.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">EC2</td></tr>
</tbody></table>
<div class="separator" style="clear: both; text-align: center;">
<br /></div>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<div style="text-align: left;">
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">2. Select Launch Instance</span></div>
<div style="text-align: left;">
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Click on Launch Instance sub-menu to fire a new EC2 instance.</span></div>
<div style="text-align: left;">
<br /></div>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://3.bp.blogspot.com/-JuIw0vOeNGc/WZgq5MOlnII/AAAAAAAACHc/TmcmLvyjpCwUnTNI-Na2PNgz9-7A3YYygCEwYBhgL/s1600/2.%2BLaunch%2BInstance.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="518" data-original-width="820" height="202" src="https://3.bp.blogspot.com/-JuIw0vOeNGc/WZgq5MOlnII/AAAAAAAACHc/TmcmLvyjpCwUnTNI-Na2PNgz9-7A3YYygCEwYBhgL/s320/2.%2BLaunch%2BInstance.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Launch Instance</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">3. Choose an AMI (Amazon Machine Image)&nbsp;</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Amazon AMI's are basically pre-configured OS images. There are variety of images available like Windows, </span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Redhat,Ubuntu,Suse etc., select AMI&nbsp;</span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;">as per requirement and need.</span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Here we are going to select RHEL 7&nbsp;</span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">image.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://2.bp.blogspot.com/-WRUuCFTa82Q/WZgq5wpBUHI/AAAAAAAACIw/2u2I15WBYwcirOdcrNpUjWZD_tw5QoQ_gCEwYBhgL/s1600/3.%2BChoose%2BAMI.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="399" data-original-width="1305" height="97" src="https://2.bp.blogspot.com/-WRUuCFTa82Q/WZgq5wpBUHI/AAAAAAAACIw/2u2I15WBYwcirOdcrNpUjWZD_tw5QoQ_gCEwYBhgL/s320/3.%2BChoose%2BAMI.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">AWS AMI</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<div style="text-align: left;">
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">4. Choose Instance Type</span></div>
<br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Here we choose type instance Or in simple terms capacity and configuration for our EC2 RHEL instance.</span><br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://3.bp.blogspot.com/-v7uxyctl3E8/WZgq56SgBTI/AAAAAAAACIw/qmvMBeWwwcAQOv6P-WHwi0Uj-yHS0JwDwCEwYBhgL/s1600/4.%2BSelect%2BInstance%2BType.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="545" data-original-width="1346" height="129" src="https://3.bp.blogspot.com/-v7uxyctl3E8/WZgq56SgBTI/AAAAAAAACIw/qmvMBeWwwcAQOv6P-WHwi0Uj-yHS0JwDwCEwYBhgL/s320/4.%2BSelect%2BInstance%2BType.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">AWS EC2 Instance Types</td></tr>
</tbody></table>
<br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">5. Configure Instance details</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Under this step we basically configure our system with set of configurations like Network and Sub-net </span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">configurations(VPC),number of instances to be launched, instance access configurations(IAM) &amp;&nbsp;</span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 11pt;">shutdown&nbsp;</span></span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;">behavior</span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">&nbsp;etc.</span><br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://4.bp.blogspot.com/-vWkRXb55cbk/WZgq6BTPaCI/AAAAAAAACIw/VjFSbQlpsWg6KmWPqqe93yzD1LE75LT9QCEwYBhgL/s1600/5.%2BConfigure%2BInstance%2BDetails.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="557" data-original-width="1335" height="133" src="https://4.bp.blogspot.com/-vWkRXb55cbk/WZgq6BTPaCI/AAAAAAAACIw/VjFSbQlpsWg6KmWPqqe93yzD1LE75LT9QCEwYBhgL/s320/5.%2BConfigure%2BInstance%2BDetails.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Configure Instance Details</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">6. Add Storage</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Step where we configure Or attach additional storage volumes to our instance as per our&nbsp;</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">requirement/needs.</span><br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-31WqiNoZi-g/WZgq6cTkCsI/AAAAAAAACIw/-vyYxxUKM9k0rdBoNEumHT8dZ4J4ywpdQCEwYBhgL/s1600/6.%2BAdd%2BStorage.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="560" data-original-width="1342" height="133" src="https://1.bp.blogspot.com/-31WqiNoZi-g/WZgq6cTkCsI/AAAAAAAACIw/-vyYxxUKM9k0rdBoNEumHT8dZ4J4ywpdQCEwYBhgL/s320/6.%2BAdd%2BStorage.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Add Storage</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Please note EBS i.e. elastic block storage is a term generally used for storage volumes in AWS</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">7. Assign Tags</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">Optionally you can assign a tags &nbsp;like name to your instance to follow any sort of naming convention.</span><br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://4.bp.blogspot.com/-8KY6Nz9KtZU/WZgq62LeAgI/AAAAAAAACIw/yE2mUU6cu1IiyTmYwn0MFXHKhLkDuPhSQCEwYBhgL/s1600/7.%2BAdd%2BTags.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="553" data-original-width="1353" height="130" src="https://4.bp.blogspot.com/-8KY6Nz9KtZU/WZgq62LeAgI/AAAAAAAACIw/yE2mUU6cu1IiyTmYwn0MFXHKhLkDuPhSQCEwYBhgL/s320/7.%2BAdd%2BTags.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Add Tags</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">8. Create Security Groups</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">Security Groups is one of the feature provided by AWS EC2 by which you can setup various sets of firewalls&nbsp;</span></span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;">for incoming and outgoing traffic from/to your instances.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-DcRz428J-7Y/WZgq6_KNgpI/AAAAAAAACIw/y_P_ymb__KEbiWnIbLGdmwEHHY06AmrCQCEwYBhgL/s1600/8.%2BSecurity%2BGroups.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="548" data-original-width="1346" height="130" src="https://1.bp.blogspot.com/-DcRz428J-7Y/WZgq6_KNgpI/AAAAAAAACIw/y_P_ymb__KEbiWnIbLGdmwEHHY06AmrCQCEwYBhgL/s320/8.%2BSecurity%2BGroups.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Security Groups</td></tr>
</tbody></table>
<div class="separator" style="clear: both; text-align: center;">
<br /></div>
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-VZm0vHmwsMM/WZiIovGYf6I/AAAAAAAACJE/j3glaRFXC6Qt4-IjxCxzojhnn_rcMLZIgCLcBGAs/s1600/8.1%2BSG2.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="401" data-original-width="962" height="133" src="https://1.bp.blogspot.com/-VZm0vHmwsMM/WZiIovGYf6I/AAAAAAAACJE/j3glaRFXC6Qt4-IjxCxzojhnn_rcMLZIgCLcBGAs/s320/8.1%2BSG2.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Setting Up Incoming/Outgoing Firewalls</td></tr>
</tbody></table>
<div class="separator" style="clear: both; text-align: center;">
</div>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">Here we are allowing SSH default port i.e. port 22 to allow ssh access to our instance.</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">9. Review and Launch</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;">Review your configurations as performed in steps as above and Launch :-)</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://2.bp.blogspot.com/-t0oELxTtkAM/WZgq7kwLuiI/AAAAAAAACIw/rqvOdrTK944dvsr9lN7DW735eE8RyaQ4ACEwYBhgL/s1600/9.%2BReview%2Band%2BLaunch.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="558" data-original-width="1345" height="132" src="https://2.bp.blogspot.com/-t0oELxTtkAM/WZgq7kwLuiI/AAAAAAAACIw/rqvOdrTK944dvsr9lN7DW735eE8RyaQ4ACEwYBhgL/s320/9.%2BReview%2Band%2BLaunch.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Review and Launch</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">Please note while Launching AWS will ask to select available key-pair option i.e. to use an existing key-pair Or create a new key-pair. KP (key-pair) is basically used while login onto an instance and is part of one of the security that is provided by AWS.</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">10. Keypair</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;A. Select option - Create a new key-pair and provide a name for it.</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;B. Download key-pair.</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;C. Once downloaded Click Launch Instances</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-NzmnLdImUiA/WZgq71uGQOI/AAAAAAAACIw/7ON25TO1-JMYST33pmQRnqTLEWyxtPXygCEwYBhgL/s1600/Create-Download%2Bkeypair.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="501" data-original-width="689" height="232" src="https://1.bp.blogspot.com/-NzmnLdImUiA/WZgq71uGQOI/AAAAAAAACIw/7ON25TO1-JMYST33pmQRnqTLEWyxtPXygCEwYBhgL/s320/Create-Download%2Bkeypair.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Setup KeyPair</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">11. Launch Status</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">Post launching an instance AWS Console Show you launch status page. Now again click on Services -&gt; EC2 and check for running&nbsp;</span></span><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 14.6667px;">instances</span><br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://4.bp.blogspot.com/-01D3LZpxsGY/WZiIotsHI0I/AAAAAAAACJA/TP8IVDmsUAkp7oMVAzotWC6cWq-kSE14wCEwYBhgL/s1600/10.%2BLaunch%2BStatus.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="459" data-original-width="1314" height="111" src="https://4.bp.blogspot.com/-01D3LZpxsGY/WZiIotsHI0I/AAAAAAAACJA/TP8IVDmsUAkp7oMVAzotWC6cWq-kSE14wCEwYBhgL/s320/10.%2BLaunch%2BStatus.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Launch Status</td></tr>
</tbody></table>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-U9d9H0xwPXo/WZgq9Ixf8eI/AAAAAAAACIw/_B0FtK95BY4jRlhRqhNUbNuQIWQfd70egCPcBGAYYCw/s1600/Running%2BInstances.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="187" data-original-width="964" height="62" src="https://1.bp.blogspot.com/-U9d9H0xwPXo/WZgq9Ixf8eI/AAAAAAAACIw/_B0FtK95BY4jRlhRqhNUbNuQIWQfd70egCPcBGAYYCw/s320/Running%2BInstances.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Running Instances</td></tr>
</tbody></table>
<div class="separator" style="clear: both; text-align: center;">
</div>
<br />
<br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">12. Details for Launched/Running Instance</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Select running instances reference link to see details for all running instances.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://3.bp.blogspot.com/-CwxULXKrbJ8/WZiIohyK3xI/AAAAAAAACJI/iDcmfTkP31A9LZR8l8GoZ3JVvHS8PKCUQCEwYBhgL/s1600/Instance.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="339" data-original-width="1286" height="84" src="https://3.bp.blogspot.com/-CwxULXKrbJ8/WZiIohyK3xI/AAAAAAAACJI/iDcmfTkP31A9LZR8l8GoZ3JVvHS8PKCUQCEwYBhgL/s320/Instance.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Instances</td></tr>
</tbody></table>
<div class="separator" style="clear: both; text-align: center;">
</div>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Select any particular instance to see attached details to that instance like IP/VPC/State/Region etc.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://4.bp.blogspot.com/-A61iHND5CyE/WZgq8fdo_3I/AAAAAAAACIw/iwjmG1oxLdgmkcQLSeq9qYRCiL4pJd7-wCPcBGAYYCw/s1600/Instance%2BDetails.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="354" data-original-width="1125" height="100" src="https://4.bp.blogspot.com/-A61iHND5CyE/WZgq8fdo_3I/AAAAAAAACIw/iwjmG1oxLdgmkcQLSeq9qYRCiL4pJd7-wCPcBGAYYCw/s320/Instance%2BDetails.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Instance Details</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">13. Connecting to an instance</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Now we have successfully launched an instance but wondering &nbsp;how we connect to it ?</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">To connect to an AWS EC2 instance we have to use key-pair that we generated while launching an instance. We also kept/allowed SSH port to login to RHEL instance via same.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Under EC2 tab there is an option CONNECT which shows straight forward steps to login onto an instance.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-zkZOkPwE5kM/WZgq7tk3rOI/AAAAAAAACIw/yldv4qKvcBYEyboDtpOX7LM0cDQAW6fBwCPcBGAYYCw/s1600/ConnectTo%2BInstance.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="520" data-original-width="704" height="236" src="https://1.bp.blogspot.com/-zkZOkPwE5kM/WZgq7tk3rOI/AAAAAAAACIw/yldv4qKvcBYEyboDtpOX7LM0cDQAW6fBwCPcBGAYYCw/s320/ConnectTo%2BInstance.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Connect to an Instance</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Default terminal/shell can be used to SSH onto EC2 instance via Linux machines and tools like Putty/Xshell can be used to jump from windows boxes.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">SSH &nbsp;--&gt;&nbsp;</span><i style="color: #1f497d; font-family: calibri, sans-serif; font-size: 11pt;">ssh -i &lt;key-pair&gt; ec2-user@&lt;IP of EC2 instance&gt;</i><span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif; font-size: 11pt;">&nbsp;</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://3.bp.blogspot.com/-s5VBzD-7QwQ/WZgq8y_8rVI/AAAAAAAACIw/OBlH4rnOpZcsgNk1bgpsxCEljqa5kK0MwCPcBGAYYCw/s1600/Login%2Bto%2BEC2%2BInstance.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="130" data-original-width="759" height="54" src="https://3.bp.blogspot.com/-s5VBzD-7QwQ/WZgq8y_8rVI/AAAAAAAACIw/OBlH4rnOpZcsgNk1bgpsxCEljqa5kK0MwCPcBGAYYCw/s320/Login%2Bto%2BEC2%2BInstance.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">SSH from Linux Box</td></tr>
</tbody></table>
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://1.bp.blogspot.com/-sNJxZuheWO0/WZgq9MExEVI/AAAAAAAACIw/bBNDjyyKRjId76CBk4D4nIzm5vNElYWTQCPcBGAYYCw/s1600/Run%2BCommands%2Bon%2BInstance.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="204" data-original-width="600" height="108" src="https://1.bp.blogspot.com/-sNJxZuheWO0/WZgq9MExEVI/AAAAAAAACIw/bBNDjyyKRjId76CBk4D4nIzm5vNElYWTQCPcBGAYYCw/s320/Run%2BCommands%2Bon%2BInstance.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Running Commands on EC2 Instance</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">14. Terminate an Instance</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;">Its always a best practice to terminate an instance when same is not in use which in terms save overall cost for using various services as AWS billing is based upon pay-as-per-usage policy.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<br />
<table align="center" cellpadding="0" cellspacing="0" class="tr-caption-container" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody>
<tr><td style="text-align: center;"><a href="https://4.bp.blogspot.com/-TtwxmymOgSk/WZgq9oHK8NI/AAAAAAAACIw/F4KuSsEVYPcQNrZqCwOhqpNgBZSW-oJvQCPcBGAYYCw/s1600/Terminate-2.JPG" imageanchor="1" style="margin-left: auto; margin-right: auto;"><img border="0" data-original-height="358" data-original-width="960" height="119" src="https://4.bp.blogspot.com/-TtwxmymOgSk/WZgq9oHK8NI/AAAAAAAACIw/F4KuSsEVYPcQNrZqCwOhqpNgBZSW-oJvQCPcBGAYYCw/s320/Terminate-2.JPG" width="320" /></a></td></tr>
<tr><td class="tr-caption" style="text-align: center;">Terminate an Instance</td></tr>
</tbody></table>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br />After termination status of an EC2 instance will changed to "terminated" and same will automatically vanish from the instances list after some default time frame.</span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">Thank You Friends for reading out through this blog , please do post your comments for any sorts of queries or feedback!!!</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;"><br /></span></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , sans-serif;"><span style="font-size: 14.6667px;">--Avi</span></span><br />
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span>
<span style="color: #1f497d; font-family: &quot;calibri&quot; , &quot;sans-serif&quot;; font-size: 11.0pt;"><br /></span></div>
