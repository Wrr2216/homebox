# Item Templates

Item templates allow you to create reusable presets with default values and custom fields for streamlined item creation. Instead of manually entering the same information for similar items, you can apply a template to automatically populate the item creation form.

## Accessing Templates

Navigate to the Templates page from the main menu to view and manage all your templates.

## Creating a Template

To create a new template:

1. Go to the Templates page
2. Click the **Create** button
3. Fill in the template details:

### Template Information

- **Template Name** (Required) - A descriptive name for your template
- **Template Description** (Optional) - Notes about when to use this template

### Default Item Values

These values will be pre-filled when you apply the template to a new item:

- **Item Name** - Default name for items created with this template
- **Item Description** - Default description
- **Quantity** - Default quantity (defaults to 1)
- **Model Number** - Default model number
- **Manufacturer** - Default manufacturer
- **Default Location** - The location where items will be stored
- **Labels** - Labels to automatically apply to new items
- **Insured** - Whether items are marked as insured by default
- **Lifetime Warranty** - Whether items have lifetime warranty by default

### Custom Fields

You can add custom fields to your template that will be included on every item created from it:

1. Click **Add** in the Custom Fields section
2. Enter a **Field Name** (e.g., "Serial Number Format", "Color")
3. Optionally enter a **Default Value**
4. Add as many custom fields as needed

::: tip
Custom fields are useful for tracking information specific to certain types of items, such as software license keys, warranty codes, or product specifications.
:::

## Applying a Template

When creating a new item:

1. Click the template icon button next to the item creation form title
2. Search for and select the template you want to use
3. The form will be pre-populated with the template's default values
4. Modify any values as needed before creating the item

> [!TIP]
> The selected template is remembered between item creations, making it easy to add multiple items of the same type.

## Managing Templates

### Viewing Template Details

Click on a template card or navigate to `/template/{id}` to view:

- Template name and description
- Creation and last updated dates
- All default values configured
- Custom fields defined

### Editing a Template

1. Open the template detail page
2. Click the **Edit** button
3. Modify any template properties
4. Click **Update** to save changes

### Duplicating a Template

To create a copy of an existing template:

1. On the Templates page, find the template you want to copy
2. Click the duplicate icon on the template card
3. A new template will be created with "(Copy)" appended to the name
4. Edit the new template to customize it

### Deleting a Template

1. On the template detail page or template card, click the **Delete** button
2. Confirm the deletion

::: warning
Deleting a template does not affect items that were previously created using it.
:::

## Common Use Cases

- **Electronics inventory**: Create a template with custom fields for serial numbers, warranty info, and purchase details
- **Books/Media**: Template with fields for author, ISBN, genre, and shelf location
- **Tools**: Template with manufacturer, model number, and storage location pre-configured
- **Consumables**: Template with default quantity and reorder location
- **Office equipment**: Template with asset tags, purchase info, and department labels
