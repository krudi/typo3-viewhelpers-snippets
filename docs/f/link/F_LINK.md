### Link Action ViewHelper

**Trigger the Snippet:** Type `fLinkAction` in your IDE or editor.

**Description:**
A ViewHelper for creating links to Extbase actions. It allows you to generate links that target specific actions within a controller, enabling dynamic navigation between various parts of your TYPO3 extension.

**Snippet Code:**

```html
<f:link.action
    action="index"
    controller="Default"
    pluginName="MyPlugin"
    extensionName="MyExtension"
    arguments="{arguments}"
>
    Link Text
</f:link.action>
```

---

### Link Action Inline

**Trigger the Snippet:** Type `fLinkActionInline` in your IDE or editor.

**Description:**
Inline version of the ViewHelper for creating links to Extbase actions. This snippet is useful for quickly embedding action links directly within Fluid expressions.

**Snippet Code:**

```html
{f:link.action(
    action: 'index',
    controller: 'Default',
    pluginName: 'MyPlugin',
    extensionName: 'MyExtension',
    arguments: {arguments}
)}
```

---

### Link Email ViewHelper

**Trigger the Snippet:** Type `fLinkEmail` in your IDE or editor.

**Description:**
Email link ViewHelper. Generates an email link with the provided email address, making it easy to add mailto links in your templates.

**Snippet Code:**

```html
<f:link.email email="example@example.com">
    Send Email
</f:link.email>
```

---

### Link Email Inline

**Trigger the Snippet:** Type `fLinkEmail` in your IDE or editor.

**Description:**
Inline version of the ViewHelper for creating an email link. Ideal for embedding email links directly within Fluid expressions.

**Snippet Code:**

```html
{f:link.email(email: 'example@example.com')}
```

---

### Link External ViewHelper

**Trigger the Snippet:** Type `fLinkExternal` in your IDE or editor.

**Description:**
A ViewHelper for creating links to external targets, such as websites outside your TYPO3 instance. This is useful for referencing external resources or partner sites.

**Snippet Code:**

```html
<f:link.external uri="https://example.com">
    Visit Example
</f:link.external>
```

---

### Link External Inline

**Trigger the Snippet:** Type `fLinkExternalInline` in your IDE or editor.

**Description:**
Inline version of the ViewHelper for creating links to external targets. Perfect for generating external URLs within inline Fluid expressions.

**Snippet Code:**

```html
{f:link.external(uri: 'https://example.com')}
```

---

### Link File ViewHelper

**Trigger the Snippet:** Type `fLinkFile` in your IDE or editor.

**Description:**
A ViewHelper for creating links to a file (FAL). This is particularly useful when you need to link to files managed in TYPO3's File Abstraction Layer (FAL), allowing for dynamic file linking in your templates.

**Snippet Code:**

```html
<f:link.file file="fileObject">
    Download File
</f:link.file>
```

---

### Link File Inline

**Trigger the Snippet:** Type `fLinkFileInline` in your IDE or editor.

**Description:**
Inline version of the ViewHelper for creating links to a file (FAL). This snippet is ideal for embedding file links directly within Fluid expressions.

**Snippet Code:**

```html
{f:link.file(file: 'fileObject')}
```

---

### Link Page ViewHelper

**Trigger the Snippet:** Type `fLinkPage` in your IDE or editor.

**Description:**
A ViewHelper for creating links to TYPO3 pages. This ViewHelper is essential for generating internal links to other pages within the TYPO3 site, ensuring seamless navigation.

**Snippet Code:**

```html
<f:link.page pageUid="1">
    Go to Home
</f:link.page>
```

---

### Link Page Inline

**Trigger the Snippet:** Type `fLinkPageInline` in your IDE or editor.

**Description:**
Inline version of the ViewHelper for creating links to TYPO3 pages. This version is perfect for generating page links directly within inline Fluid expressions.

**Snippet Code:**

```html
{f:link.page(pageUid: '1')}
```

---

### Link Typolink ViewHelper

**Trigger the Snippet:** Type `fLinkTypolink` in your IDE or editor.

**Description:**
A ViewHelper to create links from fields supported by the link wizard. This ViewHelper is useful when you want to generate links based on TYPO3's link wizard configurations.

**Snippet Code:**

```html
<f:link.typolink parameter="1">
    Go to Home
</f:link.typolink>
```

---

### Link Typolink Inline

**Trigger the Snippet:** Type `fLinkTypolinkInline` in your IDE or editor.

**Description:**
Inline version of the ViewHelper to create links from fields supported by the link wizard. This snippet is ideal for inline use when working with link wizard-generated parameters.

**Snippet Code:**

```html
{f:link.typolink(parameter: '1')} Go to Home
```
