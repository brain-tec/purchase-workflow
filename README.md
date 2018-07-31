[![Runbot Status](https://runbot.odoo-community.org/runbot/badge/flat/142/9.0.svg)](https://runbot.odoo-community.org/runbot/repo/github-com-oca-purchase-workflow-142)
[![Build Status](https://travis-ci.org/OCA/purchase-workflow.svg?branch=9.0)](https://travis-ci.org/OCA/purchase-workflow)
[![Coverage Status](https://coveralls.io/repos/OCA/purchase-workflow/badge.png?branch=9.0)](https://coveralls.io/r/OCA/purchase-workflow?branch=9.0)

Odoo modules for purchase and its workflow
==========================================

This project aim to deal with modules related to manage purchase and their related workflow. You'll find modules that:

 - Allow to easily group purchase order
 - Choose the cheapest supplier
 - Add validation step
 - ...

[//]: # (addons)

Available addons
----------------
addon | version | summary
--- | --- | ---
[procurement_purchase_no_grouping](procurement_purchase_no_grouping/) | 9.0.1.0.1 | Procurement Purchase No Grouping
[product_by_supplier](product_by_supplier/) | 9.0.1.1.0 | Show products grouped by suppliers
[product_supplier_code_purchase](product_supplier_code_purchase/) | 9.0.1.0.0 | This module adds to the purchase order line the supplier code defined in the product.
[product_supplierinfo_discount](product_supplierinfo_discount/) | 9.0.1.0.0 | Discounts in product supplier info
[purchase_date_planned_manual](purchase_date_planned_manual/) | 9.0.1.0.0 | This module makes the system to always respect the planned (or scheduled) date in PO lines.
[purchase_delivery_split_date](purchase_delivery_split_date/) | 9.0.1.0.0 | Purchase Deliveries split by date
[purchase_discount](purchase_discount/) | 9.0.1.1.0 | Purchase order lines with discounts
[purchase_fiscal_position_update](purchase_fiscal_position_update/) | 9.0.1.0.0 | Changing the fiscal position of a purchase order will auto-update purchase order lines
[purchase_location_by_line](purchase_location_by_line/) | 9.0.1.0.0 | Allows to define a specific destination location on each PO line
[purchase_open_qty](purchase_open_qty/) | 9.0.1.0.2 | Allows to identify the purchase orders that have quantities pending to invoice or to receive.
[purchase_order_analytic_search](purchase_order_analytic_search/) | 9.0.1.0.0 | Search purchase orders by analytic account. New menu entry in Purchasing to list purchase order lines.
[purchase_order_approved](purchase_order_approved/) | 9.0.1.0.0 | Add a new state 'Approved' in purchase orders.
[purchase_order_line_sequence](purchase_order_line_sequence/) | 9.0.1.0.1 | Purchase order lines with sequence number
[purchase_order_type](purchase_order_type/) | 9.0.1.1.0 | Purchase Order Type
[purchase_order_variant_mgmt](purchase_order_variant_mgmt/) | 9.0.1.0.0 | Handle the addition/removal of multiple variants from product template into the purchase order
[purchase_picking_state](purchase_picking_state/) | 9.0.1.0.0 | Add the status of all the incoming picking in the purchase order
[purchase_request](purchase_request/) | 9.0.1.0.2 | Use this module to have notification of requirements of materials and/or external services and keep track of such requirements.
[purchase_request_department](purchase_request_department/) | 9.0.1.0.0 | Purchase Request Department
[purchase_request_procurement](purchase_request_procurement/) | 9.0.1.0.1 | Purchase Request Procurement
[purchase_request_to_procurement](purchase_request_to_procurement/) | 9.0.1.0.1 | This module introduces the possiblity to create procurement order from purchase request
[purchase_request_to_requisition](purchase_request_to_requisition/) | 9.0.1.0.0 | Purchase Request to Call for Bids
[purchase_request_to_rfq](purchase_request_to_rfq/) | 9.0.1.0.2 | This module adds the possibility to create or update Requests for Quotation (RFQ) from Purchase Request Lines.
[purchase_request_to_rfq_order_approved](purchase_request_to_rfq_order_approved/) | 9.0.1.0.0 | Purchase Request to RFQ Order Approved
[purchase_tier_validation](purchase_tier_validation/) | 9.0.1.1.0 | Extends the functionality of Purchase Orders to support a tier validation process.
[subcontracted_service](subcontracted_service/) | 9.0.1.0.0 | Subcontracted service


Unported addons
---------------
addon | version | summary
--- | --- | ---
[framework_agreement](framework_agreement/) | 8.0.2.0.0 (unported) | Long Term Agreement (or Framework Agreement) for purchases
[mrp_smart_purchase](mrp_smart_purchase/) | 0.2 (unported) | Smart MRP Purchase based on supplier price
[procurement_batch_generator](procurement_batch_generator/) | 8.0.0.1.0 (unported) | Wizard to create procurements from product variants
[purchase_all_shipments](purchase_all_shipments/) | 8.0.1.0.0 (unported) | Purchase All Shipments
[purchase_delivery_address](purchase_delivery_address/) | 8.0.1.1.0 (unported) | Deprecated: install purchase_transport_multi_address and stock_transport_multi_address instead
[purchase_delivery_term](purchase_delivery_term/) | 0.2 (unported) | Delivery term for purchase orders
[purchase_group_hooks](purchase_group_hooks/) | 0.1 (unported) | Add hooks to the merge PO feature.
[purchase_group_orders](purchase_group_orders/) | 0.4 (unported) | Purchase Group Orders by Shop and Carrier
[purchase_landed_costs](purchase_landed_costs/) | 1.0.1 (unported) | Purchase Landed Costs
[purchase_last_price_info](purchase_last_price_info/) | 8.0.1.0.0 (unported) | Product Last Price Info - Purchase
[purchase_multi_picking](purchase_multi_picking/) | 0.2 (unported) | Multi Pickings from Purchase Orders
[purchase_order_force_number](purchase_order_force_number/) | 0.1 (unported) | Force purchase orders numeration
[purchase_order_revision](purchase_order_revision/) | 8.0.1.0.0 (unported) | Purchase order revisions
[purchase_origin_address](purchase_origin_address/) | 8.0.1.0.0 (unported) | Deprecated: use purchase_transport_multi_address from OCA/stock-logistics-transport
[purchase_partial_invoicing](purchase_partial_invoicing/) | 8.0.0.1.0 (unported) | Purchase partial invoicing
[purchase_partner_invoice_method](purchase_partner_invoice_method/) | 8.0.1.0.0 (unported) | Adds supplier invoicing control on partner form
[purchase_requisition_auto_rfq](purchase_requisition_auto_rfq/) | 8.0.0.2.0 (unported) | Automatically create RFQ from a purchase requisition
[purchase_requisition_auto_rfq_bid_selection](purchase_requisition_auto_rfq_bid_selection/) | 8.0.0.1.0 (unported) | Bridge module for PR Auto RFQ / Bid Selection
[purchase_requisition_bid_selection](purchase_requisition_bid_selection/) | 8.0.2.1.0 (unported) | Purchase Requisition Bid Selection
[purchase_requisition_delivery_address](purchase_requisition_delivery_address/) | 8.0.0.2.0 (unported) | Deprecated: install purchase_requisition_transport_multi_address instead
[purchase_requisition_multicurrency](purchase_requisition_multicurrency/) | 8.0.0.1.0 (unported) | Purchase Requisition Multicurrency
[purchase_requisition_transport_document](purchase_requisition_transport_document/) | 8.0.0.1.0 (unported) | Add Transport Documents to Purchase Requisitions
[purchase_rfq_bid_workflow](purchase_rfq_bid_workflow/) | 8.0.0.3.0 (unported) | Improve the purchase workflow to manage RFQ, Bids, and Orders
[purchase_transport_document](purchase_transport_document/) | 8.0.0.1.0 (unported) | Add a new Transport Document object in the Purchase Order
[vendor_consignment_stock](vendor_consignment_stock/) | 8.0.0.2.0 (unported) | Manage stock in our warehouse that is owned by a vendor

[//]: # (end addons)
