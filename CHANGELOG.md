# ims-bootstrap Changelog

## 1.3.0

* Added `widgets.ModelWidgets` helper to use in `Meta.widgets` to automatically create bootstrap widgets
* Changed checkbox rendering to use `label.checkbox-inline` instead of `div.checkbox` with a `label` inside
* Updated bootstrap-datepicker to version 1.6.4

## 1.3.1

* Added a standalone `glyphicons.css` file for optionally loading glyphicons (not loaded by default)

## 1.3.2

* Added a `DateTimeInput` widget

## 1.3.3

* Added `aria-describedby` attribute to fields with help text or errors

## 1.3.4

* Respect pre-existing `aria-describedby` set on widgets
* Add an `id` to each `form-group`

## 1.3.5

* Handle fields without a `formfield` in `widgets.ModelWidgets`

## 1.3.6

* Pass kwargs from `bootstrap_form`, `bootstrap_field`, and `render_value` through to the template
* Added a `render_readonly` templatetag for form fields; checks for `render_readonly` method on widgets

## 1.3.7

* Make sure hidden fields do not render a label, and do not render at all in render_readonly

## 1.3.8

* Django 1.11 compatibility
