---
title: "Risk & Compliance Feeds Schema Reference"

rightPanel: OFF
---

# Risk & Compliance Feeds Schemas

## Overview

Risk & Compliance feeds are available in XML (Extensible Markup Language), CSV (Comma-Separated Values) and XLS (Excel Binary File) formats.

<div id="XML-and-CSV-Schemas"></div>

## XML and CSV Schemas

The following table details the applicable XML and CSV Schemas for each Risk & Compliance feed.

**Important**: [Log In](/auth0/login) or [Request a Trial](/site/global/request-trial/) to access the documentation for each schema and feed.

<table>
    <tr style="font-weight:bold;">
        <td>Feed Family</td>
        <td>Feed <i class="fa fa-lock"></i></td>
        <td>XML Schema <i class="fa fa-lock"></i></td>
        <td>CSV Schema <i class="fa fa-lock"></i></td>
    </tr>
    <tr>
        <td rowspan=12>Watchlist</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/">Standard Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/no_sip_crime_filtered_feeds/">Filtered Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/denied_party_lists_sap_gts/">Denied Party Lists SAP GTS Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist_denied_party_lists/">Watchlist Denied Party Lists XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/delta_tracker_feed/">Delta Tracker Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist_delta_tracker/">Watchlist Delta Tracker XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_delta_tracker/">Watchlist Delta Tracker CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/profile_statistics/">Profile Statistics Feed</a></td>
        <td><a href="#xls-details">Not available in XML*</a></td>
        <td><a href="#xls-details">Not available in CSV*</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/reference_mapping_feeds/">Reference Mapping Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist_reference_mapping/">Watchlist Reference Mapping XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/sanctions_control_ownership/">Sanctions Control &amp; Ownership Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/sanctions_control_ownership_sap_gts/">Sanctions Ownership Research SAP GTS Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist_denied_party_lists/">Watchlist Denied Party Lists XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/trifecta/">Trifecta Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/trifecta/sap_bis_feed/">SAP Business Integrity Screening (BIS) Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_sap_bis/">SAP BIS XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist_adverse_media_entities/">Watchlist and Adverse Media Entities Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist_state_owned_companies/">Watchlist and State-Owned Companies Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td rowspan=6>Lists for Payments &amp; Transactions Screening</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/lpts/">Basic Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_lpts_basic/">LPTS Basic XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_lpts_basic/">LPTS Basic CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/lpts/">Core Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_lpts_core/">LPTS Core XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/lpts/cities_and_ports/">Cities &amp; Ports Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/lpts/linguistic_research_china/">Sanctions Linguistic Research - China Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_lpts_core/">LPTS Core XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/lpts/linguistic_research_japan/">Sanctions Linguistic Research - Japan Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_lpts_core/">LPTS Core XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/lpts/iran_file/">Iran File Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td rowspan=2>Adverse Media Entities</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/adverse_media/">Adverse Media Entities Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist_adverse_media_entities/">Watchlist and Adverse Media Entities Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td rowspan=2>State-Owned Companies</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/state_owned_companies/">State-Owned Companies Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_state_owned_companies/">State-Owned Companies XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_state_owned_companies/">State-Owned Companies CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist_state_owned_companies/">Watchlist and State-Owned Companies Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td>Not available in CSV</td>
    </tr>
    <tr>
        <td rowspan=1>Dual-Use Goods</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/dual_use_goods/">Dual-Use Goods Feed</a></td>
        <td>Not available in XML</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/dual_use_goods/">The Dual-Use Goods schema is included in the Feed guide.</a></td>
    </tr>
    <tr>
        <td rowspan=2>Marijuana-Related Businesses / Money Services Business</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/mrb_msb_feed/">Marijuana-Related Businesses / Money Services Business Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/marijuana_related_businesses_feeds/">Marijuana-Related Businesses Feed</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
    <tr>
        <td>Custom Feeds</td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/watchlist/custom_feeds/">Custom Feeds</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/xml/xml_watchlist/">Watchlist XML Schema</a></td>
        <td><a href="/site/docs/risk_and_compliance_feeds/documentation/general_reference/schemas/csv/csv_watchlist_standard/">Watchlist CSV Schema</a></td>
    </tr>
</table>

<div id="xls-details"></div>

## XLS Details

Dow Jones delivers the following feeds in XLS format. For information on the structure of each feed visit:

* [Dual-Use Goods](/site/docs/risk_and_compliance_feeds/documentation/dual_use_goods/) <i class="fa fa-lock"></i>
* [Profile Statistics Feeds](/site/docs/risk_and_compliance_feeds/documentation/profile_statistics/) <i class="fa fa-lock"></i>