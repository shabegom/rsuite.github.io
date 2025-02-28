# MultiCascader

Single selection of data with hierarchical relationship structure.

- `<MultiCascader>`

## Usage

```js
import { MultiCascader } from 'rsuite';
```

## Examples

<!--{demo}-->

## Props

### `<MultiCascader>`

| Property              | Type`(Default)`                                                                                            | Description                                               |
| --------------------- | ---------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| appearance            | enum: 'default', 'subtle' `('default')`                                                                    | Set picker appearence                                     |
| block                 | boolean                                                                                                    | Blocking an entire row                                    |
| cascade               | boolean `(true)`                                                                                           | whether cascade select                                    |
| childrenKey           | string `('children')`                                                                                      | Set children key in data                                  |
| classPrefix           | string `('picker')`                                                                                        | The prefix of the component CSS class                     |
| cleanable             | boolean `(true)`                                                                                           | Whether the selected value can be cleared                 |
| container             | HTMLElement or (() => HTMLElement)                                                                         | Sets the rendering container                              |
| countable             | boolean `(true)`                                                                                           | Can count selected options                                |
| data \*               | Array&lt;[DataItemType](#types)&gt;                                                                        | The data of component                                     |
| defaultOpen           | boolean                                                                                                    | Default value of open property                            |
| defaultValue          | string[]                                                                                                   | Default values of the selected items                      |
| disabled              | boolean                                                                                                    | Disabled component                                        |
| disabledItemValues    | string[]                                                                                                   | Disabled items                                            |
| height                | number `(320)`                                                                                             | The height of Dropdown                                    |
| labelKey              | string `('label')`                                                                                         | Set label key in data                                     |
| menuHeight            | number `(200)`                                                                                             | Sets the height of the menu                               |
| menuWidth             | number `(156)`                                                                                             | Sets the width of the menu                                |
| onChange              | (value:string[] , event)=>void                                                                             | Callback fired when value change                          |
| onClose               | ()=>void                                                                                                   | Callback fired when close component                       |
| onClean               | (event:SyntheticEvent)=>void                                                                               | Callback fired when value clean                           |
| onGroupTitleClick     | (event)=>void                                                                                              | Callback fired when click the group title                 |
| onOpen                | ()=>void                                                                                                   | Callback fired when open component                        |
| onSelect              | (item:[DataItemType](#types), activePaths: Array, concat:(data, children)=>Array)=>void                    | Callback fired when item is selected                      |
| onSearch              | (searchKeyword:string, event)=>void                                                                        | callback function for Search                              |
| open                  | boolean                                                                                                    | Whether open the component                                |
| placeholder           | React.Node `('Select')`                                                                                    | Setting placeholders                                      |
| placement             | enum: [PlacementStart](#types)`('bottomStart')`                                                            | The placement of component                                |
| preventOverflow       | boolean                                                                                                    | Prevent floating element overflow                         |
| renderMenu            | (children: object[], menu:React.Node, parentNode?: object)=>React.Node                                     | Customizing the Rendering Menu list                       |
| renderMenuItem        | (label:React.Node, item: [DataItemType](#types))=>React.Node                                               | Custom render menu items                                  |
| renderValue           | (value:string[],selectedItems: Array&lt;[DataItemType](#types)&gt;,selectedElement:React.Node)=>React.Node | Custom render selected items                              |
| renderExtraFooter     | ()=>React.Node                                                                                             | custom render extra footer                                |
| searchable            | boolean `(true)`                                                                                           | Whether you can search for options.                       |
| size                  | enum: 'lg', 'md', 'sm', 'xs' `('md')`                                                                      | A picker can have different sizes                         |
| toggleComponentClass  | React.ElementType `('a')`                                                                                  | You can use a custom element for this component           |
| uncheckableItemValues | string[]                                                                                                   | Set the option value for the check box not to be rendered |
| value                 | string[]                                                                                                   | Specifies the values of the selected items(Controlled)    |
| valueKey              | string `('value')`                                                                                         | Set value key in data                                     |
