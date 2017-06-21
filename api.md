# Summary

| Members | Descriptions |
| --- | --- |
|  | `namespace`[`Kordata::KForms`](#namespace_kordata_1_1_k_forms) |

# namespace `Kordata::KForms`

## Summary

| Members | Descriptions |
| --- | --- |
|  | `enum`[`FieldType`](#namespace_kordata_1_1_k_forms_1a05a2d8950de9214d6d6ff3f8ef20ba3d) |
|  | `class`[`Kordata::KForms::FieldTypeExtensions`](#class_kordata_1_1_k_forms_1_1_field_type_extensions) |
| `class`[`Kordata::KForms::KField`](#class_kordata_1_1_k_forms_1_1_k_field) | [KField](#class_kordata_1_1_k_forms_1_1_k_field) class |
| `class`[`Kordata::KForms::NumberField`](#class_kordata_1_1_k_forms_1_1_number_field) | Number Field |
| `class`[`Kordata::KForms::TextInputField`](#class_kordata_1_1_k_forms_1_1_text_input_field) | Text Input Field |

## Members

#### `enum`[`FieldType`](#namespace_kordata_1_1_k_forms_1a05a2d8950de9214d6d6ff3f8ef20ba3d)

| Values | Descriptions |
| --- | --- |
|  | AdvancedObjectSelect |
|  | BarCode |
|  | ButtonBar |
|  | Calculation |
|  | CheckBox |
|  | Currency |
|  | DateAndTimePicker |
|  | DatePicker |
|  | DropDown |
|  | Geolocation |
|  | LineItems |
|  | MonthYearPicker |
|  | Number |
|  | ObjectSelect |
|  | ObjectSummary |
|  | Password |
|  | Photo |
|  | Signature |
|  | Slider |
|  | Stepper |
|  | Switch |
|  | TextDisplay |
|  | TextInput |
|  | TimePicker |
|  | TimeStamp |
|  | YesNo |
|  | Undefined |

# class `Kordata::KForms::FieldTypeExtensions`

## Summary

| Members | Descriptions |
| --- | --- |


## Members

# class `Kordata::KForms::KField`

```
class Kordata::KForms::KField
  : public ObservableObject
```

[KField](#class_kordata_1_1_k_forms_1_1_k_field) class

## Summary

| Members | Descriptions |
| --- | --- |
|  | `public inline`[`KField`](#class_kordata_1_1_k_forms_1_1_k_field_1a31719bf956a63b18b5cd878a22e74850)`()` |
|  | `public inline HashSet< string >`[`GetConditionDependencies`](#class_kordata_1_1_k_forms_1_1_k_field_1ac98afa3b5be15bffaa4eb3185186506a)`()` |
|  | `public inline virtual void`[`SetUpListeners`](#class_kordata_1_1_k_forms_1_1_k_field_1a27deea845a62c3eae858584e0a6a6031)`(Dictionary< string,`[`KField`](#class_kordata_1_1_k_forms_1_1_k_field)`> fieldIndex)` |
|  | `protected inline virtual JToken`[`GetDefaultValue`](#class_kordata_1_1_k_forms_1_1_k_field_1a44de268c2e4b1e6d837d8f201955cdb5)`()` |
|  | `protected inline virtual string`[`GetDefaultPlaceholder`](#class_kordata_1_1_k_forms_1_1_k_field_1a6580dae1a9f0e35a0d25c95b83686a35)`()` |
|  | `protected inline virtual string`[`GetDefaultDisabledPlaceholder`](#class_kordata_1_1_k_forms_1_1_k_field_1a7ce158d07d8c8382f309a08ee8c3be56)`()` |
|  | `protected inline virtual bool`[`GetHasChanged`](#class_kordata_1_1_k_forms_1_1_k_field_1a0a945f532fe47e7690cbc641d0382890)`()` |
|  | `protected inline virtual IEnumerable< ValidityError >`[`GetValidityErrors`](#class_kordata_1_1_k_forms_1_1_k_field_1a8c9d4276ff420173237b80ba3239d15d)`()` |

## Members

#### `public inline`[`KField`](#class_kordata_1_1_k_forms_1_1_k_field_1a31719bf956a63b18b5cd878a22e74850)`()`

#### `public inline HashSet< string >`[`GetConditionDependencies`](#class_kordata_1_1_k_forms_1_1_k_field_1ac98afa3b5be15bffaa4eb3185186506a)`()`

#### `public inline virtual void`[`SetUpListeners`](#class_kordata_1_1_k_forms_1_1_k_field_1a27deea845a62c3eae858584e0a6a6031)`(Dictionary< string,`[`KField`](#class_kordata_1_1_k_forms_1_1_k_field)`> fieldIndex)`

#### `protected inline virtual JToken`[`GetDefaultValue`](#class_kordata_1_1_k_forms_1_1_k_field_1a44de268c2e4b1e6d837d8f201955cdb5)`()`

#### `protected inline virtual string`[`GetDefaultPlaceholder`](#class_kordata_1_1_k_forms_1_1_k_field_1a6580dae1a9f0e35a0d25c95b83686a35)`()`

#### `protected inline virtual string`[`GetDefaultDisabledPlaceholder`](#class_kordata_1_1_k_forms_1_1_k_field_1a7ce158d07d8c8382f309a08ee8c3be56)`()`

#### `protected inline virtual bool`[`GetHasChanged`](#class_kordata_1_1_k_forms_1_1_k_field_1a0a945f532fe47e7690cbc641d0382890)`()`

#### `protected inline virtual IEnumerable< ValidityError >`[`GetValidityErrors`](#class_kordata_1_1_k_forms_1_1_k_field_1a8c9d4276ff420173237b80ba3239d15d)`()`

# class `Kordata::KForms::NumberField`

```
class Kordata::KForms::NumberField
  : public Kordata.KForms.KField
```

Number Field

## Summary

| Members | Descriptions |
| --- | --- |
|  | `protected inline virtual override string`[`GetDefaultPlaceholder`](#class_kordata_1_1_k_forms_1_1_number_field_1a0f04f334aae95b7494f164cc829c0d47)`()` |
|  | `protected inline virtual override IEnumerable< ValidityError >`[`GetValidityErrors`](#class_kordata_1_1_k_forms_1_1_number_field_1ab6b7daf37e20c860313070f511b4c7d7)`()` |

## Members

#### `protected inline virtual override string`[`GetDefaultPlaceholder`](#class_kordata_1_1_k_forms_1_1_number_field_1a0f04f334aae95b7494f164cc829c0d47)`()`

#### `protected inline virtual override IEnumerable< ValidityError >`[`GetValidityErrors`](#class_kordata_1_1_k_forms_1_1_number_field_1ab6b7daf37e20c860313070f511b4c7d7)`()`

# class `Kordata::KForms::TextInputField`

```
class Kordata::KForms::TextInputField
  : public Kordata.KForms.KField
```

Text Input Field

## Summary

| Members | Descriptions |
| --- | --- |
|  | `protected inline virtual override string`[`GetDefaultPlaceholder`](#class_kordata_1_1_k_forms_1_1_text_input_field_1a7eb7eeea78f3f44f47222863275ae846)`()` |
|  | `protected inline virtual override IEnumerable< ValidityError >`[`GetValidityErrors`](#class_kordata_1_1_k_forms_1_1_text_input_field_1add71e00df6848a751bcf9b407dc12d91)`()` |

## Members

#### `protected inline virtual override string`[`GetDefaultPlaceholder`](#class_kordata_1_1_k_forms_1_1_text_input_field_1a7eb7eeea78f3f44f47222863275ae846)`()`

#### `protected inline virtual override IEnumerable< ValidityError >`[`GetValidityErrors`](#class_kordata_1_1_k_forms_1_1_text_input_field_1add71e00df6848a751bcf9b407dc12d91)`()`



