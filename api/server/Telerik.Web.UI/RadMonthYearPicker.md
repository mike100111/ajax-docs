---
title: Telerik.Web.UI.RadMonthYearPicker
page_title: Telerik.Web.UI.RadMonthYearPicker
description: Telerik.Web.UI.RadMonthYearPicker
---

# Telerik.Web.UI.RadMonthYearPicker

RadMonthYearPicker class

## Inheritance Hierarchy

* System.Object
* System.Web.UI.Control
* System.Web.UI.WebControls.WebControl
* Telerik.Web.UI.RadWebControl
* Telerik.Web.UI.Calendar.Persistence.PropertiesControl
* Telerik.Web.UI.RadMonthYearPicker

## Properties

###  LocalizationPath `MonthYearPickerStrings`

Gets or sets a value indicating where RadMonthYearPicker will look for its .resx localization file.
            By default this file should be in the App_GlobalResources folder. However, if you cannot put
            the resource file in the default location or .resx files compilation is disabled for some reason 
            (e.g. in a DotNetNuke environment), this property should be set to the location of the resource file.

#### Remarks
If specified, the LocalizationPath
            property will allow you to load the grid localization file from any location in the 
            web application.

###  Skin `String`

Gets or sets the skin name for the control user interface.

#### Remarks
If this property is not set, the control will render using the skin named "Default".
            If EnableEmbeddedSkins is set to false, the control will not render skin.

###  MonthCellsStyle `TableItemStyle`

Gets the style applied to month cells.

###  YearCellsStyle `TableItemStyle`

Gets the style applied to year cells.

###  EnableEmbeddedSkins `String`

Gets or sets the value, indicating whether to render links to the embedded skins or not.

#### Remarks
If EnableEmbeddedSkins is set to false you will have to register the needed CSS files by hand.

###  EnableEmbeddedScripts `Boolean`

Gets or sets the value, indicating whether to render script references to the embedded scripts or not.

#### Remarks
If EnableEmbeddedScripts is set to false you will have to register the needed Scripts files by hand.

###  EnableEmbeddedBaseStylesheet `Boolean`

Gets or sets the value, indicating whether to render the link to the embedded base stylesheet of the control or not.

#### Remarks
If EnableEmbeddedBaseStylesheet is set to false you will have to register the needed control base CSS file by hand.

###  RegisterWithScriptManager `Boolean`

Gets or sets the value, indicating whether to register with the ScriptManager control on the page.

#### Remarks
If RegisterWithScriptManager is set to false the control can be rendered on the page using Web Services or normal callback requests/page methods.

###  MonthYearTableView `MonthYearView`

Gets the MonthYearView instance of the MonthYearPicker control.

###  DateInput `RadDateInput`

Gets the RadDateInput instance of the RadMonthYearPicker control.

###  DatePopupButton `MonthYearPopupButton`

Gets the DatePopupButton instance of the RadMonthYearPicker control.  
            You can use the object to customize the popup button's appearance and behavior.

###  AutoPostBack `Boolean`

Gets or sets a value indicating whether a postback to the server automatically occurs when the user interacts with the control.

#### Remarks
Setting this property to true will make RadMonthYearPicker postback to the server 
            on date selection through the MonthYearView or the DateInput components.

###  Enabled `Boolean`

Gets or sets a value indicating whether the Web server control is enabled.

###  TabIndex `Int16`

Gets or sets the tab index of the Web server control.

###  HiddenInputTitleAttibute `String`

Gets or sets the title attribute for the hidden field.

###  WrapperTableSummary `String`

Gets or sets summary attribute for the table which wraps the RadMonthYearPicker controls.

#### Remarks
Setting this property to empty string will force Telerik RadMonthYearPicker to not render summary tag.

###  WrapperTableCaption `String`

Gets or sets the caption for the table which wraps the RadMonthYearPicker controls.

#### Remarks
Setting this property to empty string will force Telerik RadMonthYearPicker to not render caption tag.

###  PopupDirection `DatePickerPopupDirection`

Gets or sets the direction in which the popup MonthYearView is displayed,
            with relation to the RadMonthYearPicker control.

###  MonthYearNavigationSettings `MonthYearNavigationSettings`

Gets the subproperties can be used to modify the fast Month/Year navigation popup settings.

###  ZIndex `Int32`

Gets or sets the z-index style of the control's popups

###  RenderMode `RenderMode`

Sets the render mode of the RadDatePicker and its child controls

###  EnableShadows `Boolean`

Gets or sets whether popup shadows will appear.

###  Overlay `Boolean`

Gets or sets a value indicating whether the picker will create an overlay element to ensure popups are over a flash element or Java applet.

###  SelectedDate `Nullable`1`

Gets or sets the date content of RadMonthYearPicker.

###  ValidationDate `String`

This property is used by the RadDateInput's internals only. It is subject to
            change in the future versions. Please do not use.

###  InvalidTextBoxValue `String`

Gets the invalid date string in the control's textbox

###  DbSelectedDate `Nullable`1`

Gets or sets the date content of RadMonthYearPicker in a database friendly way.

#### Remarks
This property behaves exactly like the SelectedDate property. The only difference
            is that it will not throw an exception if the new value is null or DBNull. Setting a
            null value will internally revert the SelectedDate to the null value, i.e. the input value will be empty.

###  IsEmpty `Boolean`

Used to determine if RadMonthYearPicker is empty.

###  EnableTyping `Boolean`

Enables or disables typing in the date input box.

###  ShowPopupOnFocus `Boolean`

Gets or sets whether the popup control is displayed when the DateInput textbox is focused.

###  MinDate `DateTime`

Gets or sets the minimal range date for selection.
            Selecting a date earlier than that will not be allowed.

#### Remarks
This property has a default value of 1/1/1980

###  MaxDate `DateTime`

Gets or sets the latest valid date for selection.
            Selecting a date later than that will not be allowed.

#### Remarks
This property has a default value of 12/31/2099

###  Culture `CultureInfo`

Gets or sets the culture used by RadMonthYearPicker to format the date.

###  FocusedDate `DateTime`

Gets or sets the  MonthYearView uses this date to focus itself whenever the date input component of the RadMonthYearPicker is empty.

###  Width `Unit`

Gets or sets the width of the RadMonthYearPicker in pixels.

###  ShowAnimation `CalendarAnimationSettings`

Gets the settings associated with showing the  its popup controls.

###  HideAnimation `CalendarAnimationSettings`

Gets the settings associated with hiding the  its popup controls.

###  ClientEvents `MonthYearPickerClientEvents`

Gets a set of properties that get or set the names of the JavaScript 
            functions that are invoked upon specific client-side events.

###  EnableAriaSupport `Boolean`

When set to true enables support for WAI-ARIA

###  ImagesPath `String`

Gets or sets default path for the grid images when EnableEmbeddedSkins is set to false.

###  IsDesignMode `Boolean`

Returns whether RadCalendar is currently in design mode.

###  FastNavigationStyle `TableItemStyle`

Gets the style properties for the Month/Year fast navigation.

###  RangeMaxDate `DateTime`

Gets or sets the maximum date valid for selection by
            Telerik RadMonthYearPicker. Must be interpreted as the Higher bound of the valid
            dates range available for selection. Telerik RadMonthYearPicker will not allow
            navigation or selection past this date.

#### Remarks
This property has a default value of 12/30/2099
            (Gregorian calendar date).

###  RegisterWithScriptManager `Boolean`

Gets or sets the value, indicating whether to register with the ScriptManager control on the page.

#### Remarks
If RegisterWithScriptManager is set to false the control can be rendered on the page using Web Services or normal callback requests/page methods.

###  Skin `String`

Gets or sets the skin name for the control user interface.

#### Remarks
If this property is not set, the control will render using the skin named "Default".
            If EnableEmbeddedSkins is set to false, the control will not render skin.

###  IsSkinSet `String`

For internal use.

###  EnableEmbeddedScripts `Boolean`

Gets or sets the value, indicating whether to render script references to the embedded scripts or not.

#### Remarks
If EnableEmbeddedScripts is set to false you will have to register the needed Scripts files by hand.

###  EnableEmbeddedSkins `String`

Gets or sets the value, indicating whether to render links to the embedded skins or not.

#### Remarks
If EnableEmbeddedSkins is set to false you will have to register the needed CSS files by hand.

###  EnableEmbeddedBaseStylesheet `Boolean`

Gets or sets the value, indicating whether to render the link to the embedded base stylesheet of the control or not.

#### Remarks
If EnableEmbeddedBaseStylesheet is set to false you will have to register the needed control base CSS file by hand.

###  RuntimeSkin `String`

Gets the real skin name for the control user interface. If Skin is not set, returns
            "Default", otherwise returns Skin.

###  EnableAjaxSkinRendering `String`

Gets or sets the value, indicating whether to render the skin CSS files during Ajax requests

#### Remarks
If EnableAjaxSkinRendering is set to false you will have to register the needed control base CSS file by hand when adding/showing the control with Ajax.

###  ClientStateFieldID `String`

###  RenderMode `RenderMode`

Specifies the rendering mode of the control. Setting the mode to Lightweight will yield
            HTML 5/CSS 3 html and css.

#### Remarks
Lightweight rendering mode might change the outlook of the component in some older browsers
            that don't support CSS3/HTML5.

###  ResolvedRenderMode `RenderMode`

Returns resolved RenderMode should the original value was Auto

###  CssClassFormatString `String`

The CssClass property will now be used instead of the former Skin 
            and will be modified in AddAttributesToRender()

###  ClientIDMode `ClientIDMode`

This property is overridden in order to support controls which implement INamingContainer.
            The default value is changed to "AutoID".

###  ScriptManager `ScriptManager`

###  RadScriptManager `ScriptManager`

## Methods

###  ConfigureDateInput

Override this method to provide any last minute configuration changes.  Make sure you call the base implementation.

#### Returns

`System.Void` 

###  Focus

Sets input focus to a control.

#### Returns

`System.Void` 

###  Clear

Clears the selected date of the RadMonthYearPicker control and displays a blank date.

#### Returns

`System.Void` 

###  WriteHiddenFieldRegistration

#### Returns

`System.Void` 

###  GetHiddenRegistration

#### Returns

`System.String` 

###  System.Web.UI.IPostBackDataHandler.LoadPostData

#### Returns

`System.Boolean` 

###  AddAttributesToRender

#### Returns

`System.Void` 

###  OnPreRender

#### Returns

`System.Void` 

###  ControlPreRender

Code moved into this method from OnPreRender to make sure it executed when the framework skips OnPreRender() for some reason

#### Returns

`System.Void` 

###  RegisterScriptControl

Registers the control with the ScriptManager

#### Returns

`System.Void` 

###  RegisterCssReferences

Registers the CSS references

#### Returns

`System.Void` 

###  LoadClientState

Loads the client state data

#### Parameters

#### clientState `System.Collections.Generic.Dictionary{System.String,System.Object}`

#### Returns

`System.Void` 

###  SaveClientState

Saves the client state data

#### Returns

`System.String` 

###  RenderClientStateField

#### Returns

`System.Void` 

###  RenderBeginTag

#### Returns

`System.Void` 

###  RenderEndTag

#### Returns

`System.Void` 

###  Render

#### Returns

`System.Void` 

###  RenderScriptsNoScriptManager

#### Returns

`System.Void` 

###  RenderDescriptorsNoScriptManager

#### Returns

`System.Void` 

###  RenderContents

#### Returns

`System.Void` 

###  ApplyConditionalRendering

Use this from RenderContents of the inheritor

#### Returns

`System.Void` 

###  DescribeComponent

#### Returns

`System.Void` 

###  DescribeProperty

#### Returns

`System.Void` 

###  DescribeIDReferenceProperty

#### Returns

`System.Void` 

###  DescribeEvent

#### Returns

`System.Void` 

###  GetEmbeddedSkinNames

Returns the names of all embedded skins. Used by Telerik.Web.Examples.

#### Returns

`System.Collections.Generic.List`1` 

###  LoadPostData

Executed when post data is loaded from the request

#### Parameters

#### postDataKey `System.String`

#### postCollection `System.Collections.Specialized.NameValueCollection`

#### Returns

`System.Boolean` 

###  RaisePostDataChangedEvent

Executed when post data changes should invoke a changed event

#### Returns

`System.Void` 
