
[![Runboat](https://img.shields.io/badge/runboat-Try%20me-875A7B.png)](https://runboat.odoo-community.org/builds?repo=OCA/sale-workflow&target_branch=14.0)
[![Pre-commit Status](https://github.com/OCA/sale-workflow/actions/workflows/pre-commit.yml/badge.svg?branch=14.0)](https://github.com/OCA/sale-workflow/actions/workflows/pre-commit.yml?query=branch%3A14.0)
[![Build Status](https://github.com/OCA/sale-workflow/actions/workflows/test.yml/badge.svg?branch=14.0)](https://github.com/OCA/sale-workflow/actions/workflows/test.yml?query=branch%3A14.0)
[![codecov](https://codecov.io/gh/OCA/sale-workflow/branch/14.0/graph/badge.svg)](https://codecov.io/gh/OCA/sale-workflow)
[![Translation Status](https://translation.odoo-community.org/widgets/sale-workflow-14-0/-/svg-badge.svg)](https://translation.odoo-community.org/engage/sale-workflow-14-0/?utm_source=widget)

<!-- /!\ do not modify above this line -->

# Odoo Sales, Workflow and Organization

This project aim to deal with modules related to manage sale and their related workflow.

<!-- /!\ do not modify below this line -->

<!-- prettier-ignore-start -->

[//]: # (addons)

Available addons
----------------
addon | version | maintainers | summary
--- | --- | --- | ---
[portal_sale_personal_data_only](portal_sale_personal_data_only/) | 14.0.1.0.0 |  | Portal Sale Personal Data Only
[pricelist_cache](pricelist_cache/) | 14.0.1.4.1 |  | Provide a new model to cache price lists and update it, to make it easier to retrieve them.
[pricelist_cache_rest](pricelist_cache_rest/) | 14.0.1.0.0 |  | Provides an endpoint to get product prices for a given customer
[product_form_sale_link](product_form_sale_link/) | 14.0.1.1.1 |  | Adds a button on product forms to access Sale Lines
[product_supplierinfo_for_customer_elaboration](product_supplierinfo_for_customer_elaboration/) | 14.0.1.0.0 |  | Allows to define default elaborations and elaboration notes on product customerinfos
[product_supplierinfo_for_customer_sale](product_supplierinfo_for_customer_sale/) | 14.0.1.2.0 |  | Loads in every sale order line the customer code defined in the product
[product_supplierinfo_for_customer_sale_blanket_order](product_supplierinfo_for_customer_sale_blanket_order/) | 14.0.1.0.0 | [![aleuffre](https://github.com/aleuffre.png?size=30px)](https://github.com/aleuffre) [![renda-dev](https://github.com/renda-dev.png?size=30px)](https://github.com/renda-dev) [![PicchiSeba](https://github.com/PicchiSeba.png?size=30px)](https://github.com/PicchiSeba) | Product Supplierinfo for Customer Sale Blanket Order
[sale_advance_payment](sale_advance_payment/) | 14.0.1.1.4 |  | Allow to add advance payments on sales and then use them on invoices
[sale_amount_payment_link](sale_amount_payment_link/) | 14.0.1.0.1 |  | Reduce Amount to be paid while Payment Link is generated on Sale Order, depending on done Transactions.
[sale_automatic_workflow](sale_automatic_workflow/) | 14.0.1.4.0 |  | Sale Automatic Workflow
[sale_automatic_workflow_delivery_state](sale_automatic_workflow_delivery_state/) | 14.0.1.0.0 |  | Glue module for sale_automatic_workflow and sale_delivery_state
[sale_automatic_workflow_ignore_exception](sale_automatic_workflow_ignore_exception/) | 14.0.1.0.2 |  | Sale automatic workflow ignore exception
[sale_automatic_workflow_invoice_default_value](sale_automatic_workflow_invoice_default_value/) | 14.0.1.0.0 |  | Sale automatic workflow invoice default values
[sale_automatic_workflow_job](sale_automatic_workflow_job/) | 14.0.1.0.3 |  | Execute sale automatic workflows in queue jobs
[sale_automatic_workflow_payment_mode](sale_automatic_workflow_payment_mode/) | 14.0.1.1.1 |  | Sale Automatic Workflow - Payment Mode
[sale_automatic_workflow_periodicity](sale_automatic_workflow_periodicity/) | 14.0.1.1.0 | [![TDu](https://github.com/TDu.png?size=30px)](https://github.com/TDu) | Adds a period for the execution of a workflow.
[sale_blanket_order](sale_blanket_order/) | 14.0.2.0.0 | [![aleuffre](https://github.com/aleuffre.png?size=30px)](https://github.com/aleuffre) [![renda-dev](https://github.com/renda-dev.png?size=30px)](https://github.com/renda-dev) [![PicchiSeba](https://github.com/PicchiSeba.png?size=30px)](https://github.com/PicchiSeba) | Blanket Orders
[sale_blanket_order_revision](sale_blanket_order_revision/) | 14.0.1.0.0 | [![aleuffre](https://github.com/aleuffre.png?size=30px)](https://github.com/aleuffre) [![renda-dev](https://github.com/renda-dev.png?size=30px)](https://github.com/renda-dev) [![PicchiSeba](https://github.com/PicchiSeba.png?size=30px)](https://github.com/PicchiSeba) | Revision feture for Blanket Orders
[sale_by_packaging](sale_by_packaging/) | 14.0.2.1.0 |  | Manage sale of packaging
[sale_cancel_confirm](sale_cancel_confirm/) | 14.0.1.0.0 | [![kittiu](https://github.com/kittiu.png?size=30px)](https://github.com/kittiu) | Sales Cancel Confirm
[sale_cancel_reason](sale_cancel_reason/) | 14.0.1.1.1 |  | Sale Cancel Reason
[sale_commercial_partner](sale_commercial_partner/) | 14.0.1.0.1 |  | Add stored related field 'Commercial Entity' on sale orders
[sale_commitment_date_mandatory](sale_commitment_date_mandatory/) | 14.0.1.1.0 |  | Set commitment data mandatory and don't allowto add lines unless this field is filled
[sale_company_currency](sale_company_currency/) | 14.0.1.0.1 |  | Company Currency in Sale Orders
[sale_contact_type](sale_contact_type/) | 14.0.1.0.0 |  | Define ordering contact type
[sale_coupon_order_discount_fast_change_ui](sale_coupon_order_discount_fast_change_ui/) | 14.0.1.0.0 |  | This module adds an option related to the reward lines to the Sale Order Discount Fast Change UI module
[sale_default_uom](sale_default_uom/) | 14.0.1.1.1 | [![ashishhirapara](https://github.com/ashishhirapara.png?size=30px)](https://github.com/ashishhirapara) | Set default Unit of Measure value of a product in sales order lines.
[sale_delivery_date](sale_delivery_date/) | 14.0.1.1.0 | [![mmequignon](https://github.com/mmequignon.png?size=30px)](https://github.com/mmequignon) | Postpones delivery dates based on customer preferences, and/or warehouse configuration.
[sale_delivery_split_date](sale_delivery_split_date/) | 14.0.1.0.1 |  | Sale Deliveries split by date
[sale_delivery_state](sale_delivery_state/) | 14.0.2.1.0 |  | Show the delivery state on the sale order
[sale_discount_display_amount](sale_discount_display_amount/) | 14.0.2.1.0 |  | This addon intends to display the amount of the discount computed on sale_order_line and sale_order level
[sale_elaboration](sale_elaboration/) | 14.0.1.0.1 |  | Set an elaboration for any sale line
[sale_exception](sale_exception/) | 14.0.1.1.1 |  | Custom exceptions on sale order
[sale_exception_product_sale_manufactured_for](sale_exception_product_sale_manufactured_for/) | 14.0.1.1.0 |  | The partner set in the sales order can order only if he/she has a commercial entity that is listed as one of the partners for which the products can be manufactured for.
[sale_fixed_discount](sale_fixed_discount/) | 14.0.1.0.2 |  | Allows to apply fixed amount discounts in sales orders.
[sale_force_invoiced](sale_force_invoiced/) | 14.0.1.1.2 |  | Allows to force the invoice status of the sales order to Invoiced
[sale_global_discount](sale_global_discount/) | 14.0.1.1.1 |  | Sale Global Discount
[sale_invoice_auto_deliver](sale_invoice_auto_deliver/) | 14.0.1.0.1 |  | Sale Invoice Automatic Deliver
[sale_invoice_blocking](sale_invoice_blocking/) | 14.0.1.0.1 |  | Allow you to block the creation of invoices from a sale order.
[sale_invoice_delivery_state](sale_invoice_delivery_state/) | 14.0.1.0.1 |  | Sale Invoice Delivery State
[sale_invoice_no_mail](sale_invoice_no_mail/) | 14.0.1.0.1 |  | Sale Invoice No Mail
[sale_invoice_plan](sale_invoice_plan/) | 14.0.1.0.5 | [![kittiu](https://github.com/kittiu.png?size=30px)](https://github.com/kittiu) | Add to sales order, ability to manage future invoice plan
[sale_invoice_policy](sale_invoice_policy/) | 14.0.1.0.0 |  | Sales Management: let the user choose the invoice policy on the order
[sale_isolated_quotation](sale_isolated_quotation/) | 14.0.2.1.0 | [![bealdav](https://github.com/bealdav.png?size=30px)](https://github.com/bealdav) [![kittiu](https://github.com/kittiu.png?size=30px)](https://github.com/kittiu) | Sale Isolated Quotation
[sale_last_price_info](sale_last_price_info/) | 14.0.1.0.1 |  | Product Last Price Info - Sale
[sale_mail_autosubscribe](sale_mail_autosubscribe/) | 14.0.1.0.0 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Automatically subscribe partners to their company's sale orders
[sale_manual_delivery](sale_manual_delivery/) | 14.0.1.0.0 |  | Create manually your deliveries
[sale_mrp_bom](sale_mrp_bom/) | 14.0.1.0.1 |  | Allows define a BOM in the sales lines.
[sale_order_amount_to_invoice](sale_order_amount_to_invoice/) | 14.0.1.0.0 |  | Show total amount to invoice in quotations/sales orders
[sale_order_archive](sale_order_archive/) | 14.0.1.0.0 |  | Archive Sale Orders
[sale_order_carrier_auto_assign](sale_order_carrier_auto_assign/) | 14.0.1.0.1 |  | Auto assign delivery carrier on sale order confirmation
[sale_order_change_analytic_account](sale_order_change_analytic_account/) | 14.0.1.0.0 |  | This addon allow user to update analytic account on sale orders and related journal entries.
[sale_order_digitized_signature](sale_order_digitized_signature/) | 14.0.1.0.0 | [![mgosai](https://github.com/mgosai.png?size=30px)](https://github.com/mgosai) | Capture customer signature on the sales order
[sale_order_disable_user_autosubscribe](sale_order_disable_user_autosubscribe/) | 14.0.1.0.0 |  | Remove the salesperson from autosubscribed sale followers
[sale_order_discount_fast_change_ui](sale_order_discount_fast_change_ui/) | 14.0.1.0.1 |  | This module disables the slow odoo discount change wizard interface and replaces it with a non transactional faster one
[sale_order_general_discount](sale_order_general_discount/) | 14.0.3.0.1 |  | General discount per sale order
[sale_order_general_discount_payment_term](sale_order_general_discount_payment_term/) | 14.0.2.0.0 | [![odooNextev](https://github.com/odooNextev.png?size=30px)](https://github.com/odooNextev) | General discount per sale order set on payment term
[sale_order_general_discount_triple](sale_order_general_discount_triple/) | 14.0.2.0.1 | [![ashishhirapara](https://github.com/ashishhirapara.png?size=30px)](https://github.com/ashishhirapara) | General discount per sale order with triple
[sale_order_invoice_amount](sale_order_invoice_amount/) | 14.0.1.0.1 |  | Display the invoiced and uninvoiced total in the sale order
[sale_order_invoicing_finished_task](sale_order_invoicing_finished_task/) | 14.0.1.1.1 |  | Control invoice order lines if their related task has been set to invoiceable
[sale_order_line_chained_move](sale_order_line_chained_move/) | 14.0.1.1.0 | [![rousseldenis](https://github.com/rousseldenis.png?size=30px)](https://github.com/rousseldenis) | This module adds a field on sale order line to get all related move lines
[sale_order_line_date](sale_order_line_date/) | 14.0.1.2.0 |  | Adds a commitment date to each sale order line.
[sale_order_line_delivery_state](sale_order_line_delivery_state/) | 14.0.1.0.0 |  | Show the delivery state on the sale order line
[sale_order_line_description](sale_order_line_description/) | 14.0.1.0.0 |  | Sale order line description
[sale_order_line_description_single_attribute](sale_order_line_description_single_attribute/) | 14.0.1.0.0 |  | Shows single value attributes name in the sale order line description
[sale_order_line_discount_validation](sale_order_line_discount_validation/) | 14.0.2.0.1 | [![max3903](https://github.com/max3903.png?size=30px)](https://github.com/max3903) | Review discounts before sales order are printed, sent or confirmed
[sale_order_line_initial_quantity](sale_order_line_initial_quantity/) | 14.0.1.0.1 |  | Allows to display the initial quantity when the quantity has been modified on the command line.
[sale_order_line_input](sale_order_line_input/) | 14.0.1.0.0 |  | Search, create or modify directly sale order lines
[sale_order_line_menu](sale_order_line_menu/) | 14.0.1.0.0 |  | Adds a Sale Order Lines Menu
[sale_order_line_note](sale_order_line_note/) | 14.0.1.0.0 |  | Note on sale order line
[sale_order_line_packaging_qty](sale_order_line_packaging_qty/) | 14.0.1.1.1 |  | Define quantities according to product packaging on sale order lines
[sale_order_line_price_history](sale_order_line_price_history/) | 14.0.1.0.0 |  | Sale order line price history
[sale_order_line_sequence](sale_order_line_sequence/) | 14.0.2.0.0 |  | Propagates SO line sequence to invoices and stock picking.
[sale_order_lot_generator](sale_order_lot_generator/) | 14.0.1.0.2 | [![florian-dacosta](https://github.com/florian-dacosta.png?size=30px)](https://github.com/florian-dacosta) [![mourad-ehm](https://github.com/mourad-ehm.png?size=30px)](https://github.com/mourad-ehm) [![bealdav](https://github.com/bealdav.png?size=30px)](https://github.com/bealdav) | Sale Order Lot Generator
[sale_order_lot_selection](sale_order_lot_selection/) | 14.0.1.1.1 | [![bodedra](https://github.com/bodedra.png?size=30px)](https://github.com/bodedra) | Sale Order Lot Selection
[sale_order_lot_selection_by_quant](sale_order_lot_selection_by_quant/) | 14.0.1.0.1 | [![aleuffre](https://github.com/aleuffre.png?size=30px)](https://github.com/aleuffre) | Sale Order Lot Selection By Quant
[sale_order_mass_action](sale_order_mass_action/) | 14.0.1.0.0 |  | Allows to easy mass operations on sale orders.
[sale_order_note_template](sale_order_note_template/) | 14.0.1.0.0 |  | Add sale orders terms and conditions template that can be used to quickly fullfill sale order terms and conditions
[sale_order_partner_restrict](sale_order_partner_restrict/) | 14.0.1.1.0 | [![OriolVForgeFlow](https://github.com/OriolVForgeFlow.png?size=30px)](https://github.com/OriolVForgeFlow) | Apply restrictions when selecting from the list of customers on SO.
[sale_order_price_recalculation](sale_order_price_recalculation/) | 14.0.1.0.0 |  | Recalculate prices / Reset descriptions on sale order lines
[sale_order_priority](sale_order_priority/) | 14.0.1.0.0 |  | Define priority on sale orders
[sale_order_product_assortment](sale_order_product_assortment/) | 14.0.2.0.0 | [![CarlosRoca13](https://github.com/CarlosRoca13.png?size=30px)](https://github.com/CarlosRoca13) | Module that allows to use the assortments on sale orders
[sale_order_product_assortment_quick](sale_order_product_assortment_quick/) | 14.0.1.0.0 | [![renda-dev](https://github.com/renda-dev.png?size=30px)](https://github.com/renda-dev) [![aleuffre](https://github.com/aleuffre.png?size=30px)](https://github.com/aleuffre) | Bridge module between sale_order_product_assortment and sale_quick
[sale_order_qty_change_no_recompute](sale_order_qty_change_no_recompute/) | 14.0.1.0.2 | [![victoralmau](https://github.com/victoralmau.png?size=30px)](https://github.com/victoralmau) | Prevent recompute if only quantity has changed in sale order line
[sale_order_report_without_price](sale_order_report_without_price/) | 14.0.1.0.1 |  | Allow you to generate quotation and order reports without price.
[sale_order_revision](sale_order_revision/) | 14.0.1.1.1 |  | Keep track of revised quotations
[sale_order_secondary_unit](sale_order_secondary_unit/) | 14.0.1.0.1 |  | Sale product in a secondary unit
[sale_order_tag](sale_order_tag/) | 14.0.1.0.2 | [![patrickrwilson](https://github.com/patrickrwilson.png?size=30px)](https://github.com/patrickrwilson) | Adds Tags to Sales Orders.
[sale_order_type](sale_order_type/) | 14.0.3.2.0 |  | Sale Order Type
[sale_order_warn_message](sale_order_warn_message/) | 14.0.1.1.0 |  | Add a popup warning on sale to ensure warning is populated
[sale_partner_approval](sale_partner_approval/) | 14.0.2.0.0 | [![dreispt](https://github.com/dreispt.png?size=30px)](https://github.com/dreispt) | Control Partners that can be used in Sales Orders
[sale_partner_incoterm](sale_partner_incoterm/) | 14.0.1.2.0 |  | Set the customer preferred incoterm on each sales order
[sale_partner_shipping_invoice_domain](sale_partner_shipping_invoice_domain/) | 14.0.1.0.2 |  | Adds a sensible domain to the shipping and invoicing addresses on sale form view
[sale_partner_version](sale_partner_version/) | 14.0.2.0.0 |  | Sale Partner Version
[sale_pricelist_discount_decimal_precision](sale_pricelist_discount_decimal_precision/) | 14.0.1.0.1 |  | Use Discount decimal precision for pricelist items
[sale_pricelist_from_commitment_date](sale_pricelist_from_commitment_date/) | 14.0.1.0.2 |  | Use sale order commitment date to compute line price from pricelist
[sale_pricelist_item_advanced](sale_pricelist_item_advanced/) | 14.0.1.0.0 |  | Pricelist items menu
[sale_probability_amount](sale_probability_amount/) | 14.0.1.0.1 |  | add a win probability on quotation
[sale_procurement_amendment](sale_procurement_amendment/) | 14.0.1.0.0 | [![rousseldenis](https://github.com/rousseldenis.png?size=30px)](https://github.com/rousseldenis) | Allow to reflect confirmed sale lines quantity amendments to procurements
[sale_procurement_group_by_commitment_date](sale_procurement_group_by_commitment_date/) | 14.0.1.0.0 |  | Groups pickings based on commitment date of order line
[sale_procurement_group_by_line](sale_procurement_group_by_line/) | 14.0.1.0.2 |  | Base module for multiple procurement group by Sale order
[sale_product_brand_exception](sale_product_brand_exception/) | 14.0.1.0.0 |  | Define rules for sale order and brands
[sale_product_category_menu](sale_product_category_menu/) | 14.0.1.0.1 |  | Shows 'Product Categories' menu item in Sales
[sale_product_multi_add](sale_product_multi_add/) | 14.0.1.0.2 |  | Sale Product Multi Add
[sale_product_rating_verified](sale_product_rating_verified/) | 14.0.1.0.2 |  | Verify if a user has previously bought a product
[sale_product_seasonality](sale_product_seasonality/) | 14.0.1.2.0 |  | Integrates rules for products' seasonal availability with sales
[sale_product_set](sale_product_set/) | 14.0.1.5.5 |  | Sale product set
[sale_product_set_packaging_qty](sale_product_set_packaging_qty/) | 14.0.1.1.0 |  | Manage packaging and quantities on product set lines
[sale_product_set_sale_by_packaging](sale_product_set_sale_by_packaging/) | 14.0.1.0.2 |  | Glue module between `sale_by_packaging` and `sale_product_set_packaging_qty`.
[sale_promotion_rule](sale_promotion_rule/) | 14.0.1.0.1 |  | Module to manage promotion rule on sale order
[sale_promotion_rule_assortment](sale_promotion_rule_assortment/) | 14.0.1.0.0 |  | This addon allows to reduce the appliance of a promotion rule to a set of products
[sale_promotion_rule_delivery](sale_promotion_rule_delivery/) | 14.0.1.0.0 |  | Manage promotion rule with delivery
[sale_promotion_rule_display_discount_amount](sale_promotion_rule_display_discount_amount/) | 14.0.1.0.1 |  | This addon allows you to display the amount of the discount applied by the sale promotion rules on the sale order
[sale_purchase_requisition](sale_purchase_requisition/) | 14.0.1.0.1 | [![shide](https://github.com/shide.png?size=30px)](https://github.com/shide) [![anddago78](https://github.com/anddago78.png?size=30px)](https://github.com/anddago78) [![yajo](https://github.com/yajo.png?size=30px)](https://github.com/yajo) | Connect your quotations with a purchase agreement
[sale_quick](sale_quick/) | 14.0.1.0.4 |  | Quick Sale order
[sale_quick_blanket_order](sale_quick_blanket_order/) | 14.0.1.0.1 | [![PicchiSeba](https://github.com/PicchiSeba.png?size=30px)](https://github.com/PicchiSeba) [![aleuffre](https://github.com/aleuffre.png?size=30px)](https://github.com/aleuffre) | Quick Sale Blanket Orders
[sale_quick_seasonality](sale_quick_seasonality/) | 14.0.1.0.0 |  | Quick Sale order seasonality
[sale_quotation_number](sale_quotation_number/) | 14.0.2.0.2 |  | Different sequence for sale quotations
[sale_quotation_template_product_multi_add](sale_quotation_template_product_multi_add/) | 14.0.1.0.1 |  | Feature to add multiple products to quotation template
[sale_rental](sale_rental/) | 14.0.1.0.1 | [![alexis-via](https://github.com/alexis-via.png?size=30px)](https://github.com/alexis-via) | Manage Rental of Products
[sale_restricted_qty](sale_restricted_qty/) | 14.0.1.1.3 | [![alexey-pelykh](https://github.com/alexey-pelykh.png?size=30px)](https://github.com/alexey-pelykh) | Sale order min quantity
[sale_shipping_info_helper](sale_shipping_info_helper/) | 14.0.1.0.0 |  | Add shipping amounts on sale order
[sale_start_end_dates](sale_start_end_dates/) | 14.0.1.0.1 | [![alexis-via](https://github.com/alexis-via.png?size=30px)](https://github.com/alexis-via) | Adds start date and end date on sale order lines
[sale_stock_delivery_address](sale_stock_delivery_address/) | 14.0.1.0.3 |  | Sale Stock Delivery Address
[sale_stock_line_customer_ref](sale_stock_line_customer_ref/) | 14.0.1.0.0 | [![sebalix](https://github.com/sebalix.png?size=30px)](https://github.com/sebalix) | Allow you to add a customer reference on order lines propagaged to move operations.
[sale_stock_line_sequence](sale_stock_line_sequence/) | 14.0.1.0.0 |  | Glue Module for Sale Order Line Sequence and Stock Picking Line Sequence
[sale_stock_picking_blocking](sale_stock_picking_blocking/) | 14.0.1.1.2 |  | Allow you to block the creation of deliveries from a sale order.
[sale_stock_picking_note](sale_stock_picking_note/) | 14.0.1.0.0 |  | Add picking note in sale and purchase order
[sale_stock_reconcile_valuation_kit](sale_stock_reconcile_valuation_kit/) | 14.0.1.0.0 |  | Sale Stock Reconcile Valuation Kit
[sale_stock_return_request](sale_stock_return_request/) | 14.0.1.1.1 | [![chienandalu](https://github.com/chienandalu.png?size=30px)](https://github.com/chienandalu) | Sale Stock Return Request
[sale_stock_secondary_unit](sale_stock_secondary_unit/) | 14.0.1.0.0 |  | Get product quantities in a secondary unit
[sale_substate](sale_substate/) | 14.0.1.0.0 |  | Sale Sub State
[sale_tier_validation](sale_tier_validation/) | 14.0.1.1.0 |  | Extends the functionality of Sale Orders to support a tier validation process.
[sale_transaction_form_link](sale_transaction_form_link/) | 14.0.1.0.0 | [![rousseldenis](https://github.com/rousseldenis.png?size=30px)](https://github.com/rousseldenis) | Allows to display a link to payment transactions on Sale Order form view.
[sale_triple_discount](sale_triple_discount/) | 14.0.2.0.0 |  | Manage triple discount on sale order lines
[sale_validity](sale_validity/) | 14.0.1.0.2 |  | Set a default validity delay on quotations
[sale_validity_auto_cancel](sale_validity_auto_cancel/) | 14.0.1.0.0 | [![JordiMForgeFlow](https://github.com/JordiMForgeFlow.png?size=30px)](https://github.com/JordiMForgeFlow) | Automatically cancel quotations after validity period.
[sale_wishlist](sale_wishlist/) | 14.0.1.0.2 |  | Handle sale wishlist for partners
[sales_team_security](sales_team_security/) | 14.0.2.0.1 | [![pedrobaeza](https://github.com/pedrobaeza.png?size=30px)](https://github.com/pedrobaeza) [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | New group for seeing only sales channel's documents
[sales_team_security_crm](sales_team_security_crm/) | 14.0.3.0.1 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Integrates sales_team_security with crm
[sales_team_security_sale](sales_team_security_sale/) | 14.0.3.0.1 | [![ivantodorovich](https://github.com/ivantodorovich.png?size=30px)](https://github.com/ivantodorovich) | Integrates sales_team_security with sale

[//]: # (end addons)

<!-- prettier-ignore-end -->

## Licenses

This repository is licensed under [AGPL-3.0](LICENSE).

However, each module can have a totally different license, as long as they adhere to Odoo Community Association (OCA)
policy. Consult each module's `__manifest__.py` file, which contains a `license` key
that explains its license.

----
OCA, or the [Odoo Community Association](http://odoo-community.org/), is a nonprofit
organization whose mission is to support the collaborative development of Odoo features
and promote its widespread use.
