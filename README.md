# ERPNextJumpStart

A collection of links for jump starting in ERPNext Development.

## Tutorial Methods

- [Helpful Beginner Tutorial](https://frappe.school/courses/frappe-framework-tutorial)
- [Understanding Bench - Frappe - Apps](https://github.com/frappe/frappe/wiki/The-Hitchhiker%27s-Guide-to-Installing-Frapp%C3%A9-on-Linux/31019602d7f2b622e9ccb73acc766fa9541e8ec0)

## Install

- [Docker Image](https://github.com/frappe/frappe_docker)
- [Windows Based Docker Installation](https://github.com/frappe/frappe_docker/blob/main/docs/troubleshoot.md#letsencrypt-companion-not-working)

## First Steps

- [Company Setup](https://docs.erpnext.com/docs/v13/user/manual/en/setting-up/company-setup)
- [E-Mail Setup](https://docs.erpnext.com/docs/v13/user/manual/en/setting-up/email/email-account)
- [Taxes Setup](https://docs.erpnext.com/docs/v13/user/manual/en/setting-up/setting-up-taxes)

## Fields

- [Overview Field Types](https://docs.erpnext.com/docs/v13/user/manual/en/customize-erpnext/articles/field-types)
- [Link Fields](https://docs.erpnext.com/docs/v13/user/manual/en/customize-erpnext/articles/dynamic-link-fields)
- [Child Tables]()
  - create a DocType with ticked "Is ChildTable"
  - create a field in other DocType of type "Link" (link one Entitiy) or "Table" (link multiple Entities)
  - add ChildTable DocType Name in "Options"

## DocTypes

- [Link DocTypes]()

## Scripts

- [Helpful Community Scripts](https://github.com/frappe/erpnext/wiki/Community-Developed-Custom-Scripts)
- [Add Scripts to Forms](https://frappeframework.com/docs/v13/user/en/api/form)
  - Search for "Client Script" in your ERPNext Searchbar
- [Server Scripts](https://frappeframework.com/docs/v13/user/en/api/database)
- [Methods for Scripts](https://frappeframework.com/docs/v13/user/en/desk/scripting/script-api)
- [Add Button to DocType ListView](https://aadhilpm.com/button-link-in-doctype-list-view-frappe-framework-erpnext/)

## Reports

- [Report with prompt/user-input](https://frappeframework.com/docs/v13/user/en/api/dialog)
- [Example Script Report](https://discuss.erpnext.com/t/devtip-custom-reports-purely-client-side/78038)
- [Example Report with Date](https://github.com/frappe/erpnext/tree/develop/erpnext/crm/report/lead_details)
- [Multi Select Dropwdown for Filters](https://discuss.erpnext.com/t/how-can-we-add-multi-select-dropdown-filters-in-custom-script-report/69979)
- [Get and Sum Data from Customer](https://github.com/frappe/erpnext/blob/develop/erpnext/selling/report/inactive_customers/inactive_customers.py)

## API

- [Authentication](https://frappeframework.com/docs/v13/user/en/api/rest#1-token-based-authentication)
- [Get Filtered Data from API](https://discuss.erpnext.com/t/fetch-doctype-list-included-childtable-by-rest-api/83588/2?u=fgiering)
