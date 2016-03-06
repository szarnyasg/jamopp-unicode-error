# jamopp-unicode-error

Get the [jamoppc.jar](https://github.com/DevBoost/JaMoPP/blob/master/Utils/org.emftext.language.java.jamoppc/jamoppc.jar) file.

```
wget https://github.com/DevBoost/JaMoPP/raw/master/Utils/org.emftext.language.java.jamoppc/jamoppc.jar
```

Run `JaMoPPC`:

```
java -jar jamoppc.jar javadjvu0_8_09/ javadjvu.xmi
```

The following exception occurs:

```
Exception in thread "main" java.lang.RuntimeException: An invalid XML character (Unicode: 0x0) was found in the element content:
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl$Escape.convert(XMLSaveImpl.java:3398)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.getDatatypeValue(XMLSaveImpl.java:3107)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveDataTypeSingle(XMLSaveImpl.java:1692)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1274)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedMany(XMLSaveImpl.java:2411)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1547)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedSingle(XMLSaveImpl.java:2397)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1541)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedSingle(XMLSaveImpl.java:2397)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1541)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedSingle(XMLSaveImpl.java:2397)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1541)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedMany(XMLSaveImpl.java:2411)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1547)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedMany(XMLSaveImpl.java:2411)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1547)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1175)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElement(XMLSaveImpl.java:1036)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveContainedMany(XMLSaveImpl.java:2411)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1547)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveFeatures(XMLSaveImpl.java:1218)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.saveElementID(XMLSaveImpl.java:2710)
	at org.eclipse.emf.ecore.xmi.impl.XMISaveImpl.writeTopObjects(XMISaveImpl.java:84)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.traverse(XMLSaveImpl.java:589)
	at org.eclipse.emf.ecore.xmi.impl.XMLSaveImpl.save(XMLSaveImpl.java:251)
	at org.eclipse.emf.ecore.xmi.impl.XMLResourceImpl.doSave(XMLResourceImpl.java:331)
	at org.eclipse.emf.ecore.resource.impl.ResourceImpl.save(ResourceImpl.java:1417)
	at org.eclipse.emf.ecore.resource.impl.ResourceImpl.save(ResourceImpl.java:986)
	at org.emftext.language.java.jamoppc.JaMoPPC.saveXmiResource(JaMoPPC.java:164)
	at org.emftext.language.java.jamoppc.JaMoPPC.saveToSingleXMIFile(JaMoPPC.java:133)
	at org.emftext.language.java.jamoppc.JaMoPPC.main(JaMoPPC.java:109)
```
