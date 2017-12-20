# Before you Begin
This section covers the prerequisites for using the NITRO APIs, NITRO changes across releases, and limitations.

## NITRO Changes Across Releases

Some NITRO API have changed across releases. This topic details information which can help you avoid compatibility issues in your application. The changes are categorized as:

### Changes Made from 11.1-53.3 -> 12.0-48.x

**Changes across NITRO flavors**

The NITRO changes that were made in NetScaler 12.0-48.x when compared with NetScaler 11.1-53.3.

<table style="width: 523.7pt; border-collapse: collapse; border: none;" width="524">
<thead>
<tr style="height: 22.05pt;">
<td style="border: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 22.05pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Type of change</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 22.05pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Resource</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 22.05pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 22.05pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute</span></strong></p>
</td>
</tr>
</thead>
<tbody>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Resource removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vpath, vpathparam</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">ALL</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">All resources and parameters related to vpath feature.&nbsp; &nbsp;&nbsp;</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">l3param&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Icmperrgenerate</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This attribute is related to vpath for which the support is removed in 12.0.&nbsp;</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">qos_stats&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">ipcpe2qosfailedrate</span></p>
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">&nbsp;</span></strong></p>
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Note</span></strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">: Some of the counters under this resource are removed. For new definitions, see&nbsp;<a href="http://docs.citrix.com/en-us/netscaler/12/nitro-api/nitro-rest/api-reference/statistics/qos/qos.html"><span style="color: #1779ba; text-decoration: none; text-underline: none;">http://docs.citrix.com/en-us/netscaler/12/nitro-api/nitro-rest/api-reference/statistics/qos/qos.html</span></a>&nbsp;</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vrid_interface_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">trackifnum</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">New resources (vrid_trackifnum_binding and vrid6_trackifnum_binding) are introduced to deal with track interfaces.&nbsp; &nbsp;&nbsp;</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vrid_interface_binding&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">ifaces is replaced with ifnum.</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Previously, ifaces parameter was used in the response and ifnum was used in the input.&nbsp; Now both POST and GET are consistent and use the same attribute name.&nbsp; &nbsp;&nbsp;</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">sslprofile_sslciphersuite_binding&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">cipheraliasname</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">cipheraliasname is a redundant parameter. The required information is provided by ciphername parameter.</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nslicense&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Ispooledlicensing</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Ispooledlicensing Is replaced with a new parameter licensingmode which returns if the license of "Local"/"Pooled"/"CICO" type.</span></p>
</td>
</tr>
<tr style="height: 30.05pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">lbmonitor_sslcertkey_binding&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">DELETE</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.05pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">crlcheck&nbsp; &nbsp;&nbsp;</span></p>
</td>
</tr>
</tbody>
</table>

**Changes specific to NITRO SDKs**

The SDK-specific changes that were made in NetScaler 12.0-48.x when compared with NetScaler 11.1-53.3.

<table style="width: 475.3pt; border-collapse: collapse; border: none;" width="475">
<thead>
<tr>
<td style="border: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Type of change</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Class</span></strong></p>
</td>
<td style="width: 138.85pt; border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;" width="139">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method/Attribute</span></strong></p>
</td>
<td style="width: 135.0pt; border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;" width="135">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Remarks</span></strong></p>
</td>
</tr>
</thead>
<tbody>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute type changed&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">pcpmap</span></p>
</td>
<td style="width: 138.85pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="139">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">pcpprotocol</span></p>
</td>
<td style="width: 135.0pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="135">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Datatype changed from double to string.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Class removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">mediaclassification_stats</span></p>
</td>
<td style="width: 138.85pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="139">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="width: 135.0pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="135">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vxlan_iptunnel_binding&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="width: 138.85pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="139">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">add(vxlan_iptunnel_binding obj, nitro_service session)</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">delete(vxlan_iptunnel_binding obj, nitro_service session)</span></p>
</td>
<td style="width: 135.0pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="135">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Feature is deprecated, use bridgetable with broadcast mac option.&nbsp; &nbsp;&nbsp;</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed &nbsp; &nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">inatsession_stats&nbsp; &nbsp;&nbsp;</span></p>
</td>
<td style="width: 138.85pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="139">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(inatsession obj, nitro_service session)</span></p>
</td>
<td style="width: 135.0pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="135">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
</tbody>
</table>

## Changes Made from 10.5 57.x -> 11.0

**All NITRO Flavors - Changes from 10.5 57.x to 11.0**

The NITRO changes that were made in NetScaler 11.0 when compared with NetScaler 10.5 Build 57.x.

<table style="width: 326.7pt; border-collapse: collapse; border: none;" width="327">
<thead>
<tr>
<td style="width: 120.0pt; border: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt;" width="120">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Type of Change</span></strong></p>
</td>
<td style="width: 86.25pt; border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;" width="86">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Resource</span></strong></p>
</td>
<td style="width: 120.45pt; border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;" width="120">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute</span></strong></p>
</td>
</tr>
</thead>
<tbody>
<tr style="height: 30.0pt;">
<td style="width: 120.0pt; border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="120">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="width: 86.25pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="86">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nstrace</span></p>
</td>
<td style="width: 120.45pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="120">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">doruntimemerge</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="width: 120.0pt; border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="120">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="width: 86.25pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="86">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nstrace</span></p>
</td>
<td style="width: 120.45pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="120">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">tcpdump</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="width: 120.0pt; border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="120">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="width: 86.25pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="86">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">cacheobject</span></p>
</td>
<td style="width: 120.45pt; border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;" width="120">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">force</span></p>
</td>
</tr>
</tbody>
</table>

**NITRO SDKs - Changes from 10.5 57.x to 11.0**

The SDK-specific changes that were made in NetScaler 11.0 when compared with NetScaler 10.5 Build 57.x.

<table style="width: 519.75pt; border-collapse: collapse; border: none;" width="520">
<thead>
<tr>
<td style="border: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Type of Change</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Class</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replace with</span></strong></p>
</td>
</tr>
</thead>
<tbody>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute missing in method</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">cacheobject</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) flush(cacheobject obj, nitro_service session)</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">'force' attribute missing in this method.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method missing</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">clustersync</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) Force(clustersync obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) Force(nitro_service session)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method missing</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">shutdown</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) Shutdown(shutdown obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) Shutdown(nitro_service session)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method missing</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">systemfile</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(systemfile) get(systemfile obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method missing</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">sslfips</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) reset(sslfips obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) reset(nitro_service session)</span></p>
</td>
</tr>
</tbody>
</table>

### Changes made from 9.3 -> 10.1/10.5

**Note.** No changes are introduced from NetScaler 10.1 to NetScaler 10.5. Therefore, you should not face any compatibility issues when migrating from NetScaler 10.1 to 10.5.


**All NITRO Flavors - Changes from 9.3 to 10.1/10.5**

The NITRO changes that were made in NetScaler 10.1/10.5 when compared with NetScaler 9.3.

<table style="width: 519.75pt; border-collapse: collapse; border: none;" width="520">
<thead>
<tr>
<td style="border: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Type of Change</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Resource</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute</span></strong></p>
</td>
</tr>
</thead>
<tbody>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Resource removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">lbmonitor_lbmetrictable_binding</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with the resource 'lbmonitor_metric_binding'.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vserver</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">GET</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Perform the GET operation on specific virtual server types such as lb/cr/cs.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">filterpolicy</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">POST with 'action=unset'</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This method is removed as unsetting the attributes('action') of a policy makes it invalid.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">auditsyslogpolicy</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">POST with 'action=unset'</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This method is removed as unsetting the attributes('action') of a policy makes it invalid.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">auditnslogpolicy</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">POST with 'action=unset'</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This method is removed as unsetting the attributes('action') of a policy makes it invalid.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">authorizationpolicy</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">POST with 'action=unset'</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This method is removed as unsetting the attributes('action') of a policy makes it invalid.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Return-type changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">snmpengineid</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">GET</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Return type changed to an array.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Return-type changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nshostname</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">GET</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Return type changed to an array.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute-type changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">appfwpolicy_lbvserver_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">activepolicy</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Data type changed from Boolean to Integer.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute-type changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">appfwpolicy_appfwglobal_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">activepolicy</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Data type changed from Boolean to Integer.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute-type changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vlan</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">portbitmap</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Data type changed from uint to ulong.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute-type changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">vlan</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">tagbitmap</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Data type changed from uint to ulong.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">policypatset_pattern_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">indextype</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This attribute is moved to 'policypatset' resource as this attribute is applicable at patset level.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">system_stats</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">powersupply1failure</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'powersupply1status'.</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Note:&nbsp;Change is applicable from NetScaler 9.3 Build 65.8.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">system_stats</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">powersupply2failure</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'powersupply2status'.</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Note:&nbsp;Change is applicable from NetScaler 9.3 Build 65.8.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">server_servicegroup_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">servicetype</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'svctype'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">server_service_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">servicetype</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'svctype'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">crvserver</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">hits</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Hits are calculated per policy binding hence moved this parameter to binding resources.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">crvserver</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dstvsvr</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'destinationvserver'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">crvserver</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">destvserver</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'domain'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">crvserver</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsvserver</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'dnsvservername'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">appflowpolicylabel</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">type</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'policylabeltype'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">sslcipher</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">ciphgrpals</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'ciphergroupname'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">csvserver_cspolicy_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">targetvserver</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'targetlbvserver'.</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Note:&nbsp;This change is applicable for the 'sslcipher_*_binding' resources also.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">csvserver_cspolicy_binding</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">targetvserver</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'targetlbvserver'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">rewriteaction</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">allow_unsafe_pi1, allow_unsafe_pi</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replaced with 'bypassSafetyCheck'.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nsconfig</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nwfwmode</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Marked as a hidden attribute.</span></p>
</td>
</tr>
</tbody>
</table>

**NITRO SDKs - Changes from 9.3 to 10.1/10.5**

The SDK-specific changes that were made in NetScaler 10.1/10.5 when compared with NetScaler 9.3.

<table style="width: 526.5pt; border-collapse: collapse; border: none;" width="527">
<thead>
<tr>
<td style="border: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Type of Change</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Class</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method</span></strong></p>
</td>
<td style="border: solid black 1.5pt; border-left: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt;">
<p><strong><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Replace with</span></strong></p>
</td>
</tr>
</thead>
<tbody>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Class removed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Routerbgp</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">This class is removed as all router configurations are deprecated in 9.2.</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsptrrec</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(dnsptrrec obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service session, String reversedomain)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsaddrec</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(dnsaddrec obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service session, String hostname)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsnsrec</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(dnsnsrec obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service session, String domain)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">snmpengineid</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">unset(nitro_service session, String[] args)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">unset(nitro_service session, snmpengineid resource, String[] args)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">arp</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">arp.get(nitro_service session, String ipaddress)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">arp.get(nitro_service session, arp resource)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nsip</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service session, String ipaddress)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service client, nsip resource)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nsip6</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service session, String ipv6address)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">get(nitro_service session, nsip6 resource)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method signature changed</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsmxrec</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsmxrec.get(dnsmxrec obj, nitro_service session)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">dnsmxrec[] get(nitro_service service, dnsmxrec_args args)</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method Missing</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">authenticationnegotiatepolicy</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) unset(nitro_service session, String[] args, String name)' is missing in&nbsp;</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Method missing</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">authenticationnegotiatepolicy</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) unset(authenticationnegotiatepolicy obj, nitro_service session, String[] args)</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
<tr style="height: 30.0pt;">
<td style="border: solid black 1.5pt; border-top: none; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">Attribute missing in method</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">nsconfig</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">(base_response) update(nsconfig obj, nitro_service session)</span></p>
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">'nwfwmode' attribute is missing in this method.</span></p>
</td>
<td style="border-top: none; border-left: none; border-bottom: solid black 1.5pt; border-right: solid black 1.5pt; padding: 7.5pt 7.5pt 7.5pt 7.5pt; height: 30.0pt;">
<p><span style="font-size: 10.5pt; font-family: 'CitrixSans',serif; color: black;">-</span></p>
</td>
</tr>
</tbody>
</table>

###  Limitations

The section lists the NetScaler operations that cannot be performed by using NITRO API.

**Note:** These operations can be performed on the NetScaler CLI or the GUI.

* install API (supported from NetScaler 11.1 onwards)
diff API on nsconfig resource (supported from NetScaler 10.5 onwards)
* UI-internal APIs (update, unset, and get)
* show ns info
* shutdown
* Application firewall API
* importwsdl
* importcustom
* importxmlschema
* importxmlerrorpage
* importhtmlerrorpage
* rmcustom
* rmxmlschema
* rmxmlerrorpage
* rmhtmlerrorpage
* CLI-specific API
* start nstrace/stop nstrace/show nstrace
* scp
* configaudit
* show defaults
* show permission
* batch
* source