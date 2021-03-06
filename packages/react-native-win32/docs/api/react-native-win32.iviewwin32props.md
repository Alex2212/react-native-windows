<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@office-iss/react-native-win32](./react-native-win32.md) &gt; [IViewWin32Props](./react-native-win32.iviewwin32props.md)

## IViewWin32Props interface

Properties for ViewWin32 component

<b>Signature:</b>

```typescript
export interface IViewWin32Props extends Omit<RN.ViewProps, ViewWin32OmitTypes>, BasePropsWin32 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [acceptsKeyboardFocus](./react-native-win32.iviewwin32props.acceptskeyboardfocus.md) | <code>boolean</code> |  |
|  [accessibilityActions](./react-native-win32.iviewwin32props.accessibilityactions.md) | <code>ReadonlyArray&lt;AccessibilityActionInfo&gt;</code> |  |
|  [accessibilityAnnotation](./react-native-win32.iviewwin32props.accessibilityannotation.md) | <code>AccessibilityAnnotationInfo</code> | Tells a person using a screen reader what kind of annotation they have selected. If available, it will also tell a person the author of the annotation and the date and time the annotation was posted.<!-- -->Note: If typeID is 'Unknown', a typeName must be provided. |
|  [accessibilityLevel](./react-native-win32.iviewwin32props.accessibilitylevel.md) | <code>number</code> |  |
|  [accessibilityPositionInSet](./react-native-win32.iviewwin32props.accessibilitypositioninset.md) | <code>number</code> |  |
|  [accessibilitySetSize](./react-native-win32.iviewwin32props.accessibilitysetsize.md) | <code>number</code> |  |
|  [animationClass](./react-native-win32.iviewwin32props.animationclass.md) | <code>string</code> |  |
|  [children](./react-native-win32.iviewwin32props.children.md) | <code>React.ReactNode</code> |  |
|  [keyDownEvents](./react-native-win32.iviewwin32props.keydownevents.md) | <code>IHandledKeyboardEvent[]</code> |  |
|  [keyUpEvents](./react-native-win32.iviewwin32props.keyupevents.md) | <code>IHandledKeyboardEvent[]</code> |  |
|  [onBlur](./react-native-win32.iviewwin32props.onblur.md) | <code>(ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void</code> | The onBlur event occurs when an element loses focus. The opposite of onBlur is onFocus. Note that in React Native, unlike in the web, the onBlur event bubbles (similar to onFocusOut in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onBlurCapture](./react-native-win32.iviewwin32props.onblurcapture.md) | <code>(ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void</code> | The onBlur event occurs when an element loses focus. The opposite of onBlur is onFocus. Note that in React Native, unlike in the web, the onBlur event bubbles (similar to onFocusOut in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onFocus](./react-native-win32.iviewwin32props.onfocus.md) | <code>(ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void</code> | The onFocus event occurs when an element gets focus. The opposite of onFocus is onBlur. Note that in React Native, unlike in the web, the onFocus event bubbles (similar to onFocusIn in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onFocusCapture](./react-native-win32.iviewwin32props.onfocuscapture.md) | <code>(ev: RN.NativeSyntheticEvent&lt;{}&gt;) =&gt; void</code> | The onFocus event occurs when an element gets focus. The opposite of onFocus is onBlur. Note that in React Native, unlike in the web, the onFocus event bubbles (similar to onFocusIn in the web).<code>ev.target === ev.currentTarget</code> when the focus is being lost from this component. <code>ev.target !== ev.currentTarget</code> when the focus is being lost from a descendant. |
|  [onKeyDown](./react-native-win32.iviewwin32props.onkeydown.md) | <code>(args: IKeyboardEvent) =&gt; void</code> |  |
|  [onKeyDownCapture](./react-native-win32.iviewwin32props.onkeydowncapture.md) | <code>(args: IKeyboardEvent) =&gt; void</code> |  |
|  [onKeyUp](./react-native-win32.iviewwin32props.onkeyup.md) | <code>(args: IKeyboardEvent) =&gt; void</code> |  |
|  [onKeyUpCapture](./react-native-win32.iviewwin32props.onkeyupcapture.md) | <code>(args: IKeyboardEvent) =&gt; void</code> |  |
|  [onMouseEnter](./react-native-win32.iviewwin32props.onmouseenter.md) | <code>() =&gt; void</code> |  |
|  [onMouseLeave](./react-native-win32.iviewwin32props.onmouseleave.md) | <code>() =&gt; void</code> |  |
|  [tooltip](./react-native-win32.iviewwin32props.tooltip.md) | <code>string</code> | Provides a screentip to be used on hover of the view |
|  [type](./react-native-win32.iviewwin32props.type.md) | <code>React.ElementType</code> |  |

