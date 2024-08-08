* Classes:
  * NameTable - Implements a single-threaded XmlNameTable.
  * UniqueId - A unique identifier optimized for Guids.
  * XmlAttribute - Represents an attribute. Valid and default values for the attribute are defined in a document type definition (DTD) or schema.
  * XmlAttributeCollection - Represents a collection of attributes that can be accessed by name or index.
  * XmlBinaryReaderSession - Enables optimized strings to be managed in a dynamic way.
  * XmlBinaryWriterSession - Enables using a dynamic dictionary to compress common strings that appear in a message and maintain state.
  * XmlCDataSection - Represents a CDATA section.
  * XmlCharacterData - Provides text manipulation methods that are used by several classes.
  * XmlComment - Represents the content of an XML comment.
  * XmlConvert - Encodes and decodes XML names, and provides methods for converting between common language runtime types and XML Schema definition language (XSD) types. When converting data types, the values returned are locale-independent.
  * XmlDataDocument - Allows structured data to be stored, retrieved, and manipulated through a relational DataSet.
  * XmlDeclaration - Represents the XML declaration node <?xml version='1.0'...?>.
  * XmlDictionary - Implements a dictionary used to optimize Windows Communication Foundation (WCF)'s XML reader/writer implementations.
  * XmlDictionaryReader - An abstract class that the Windows Communication Foundation (WCF) derives from XmlReader to do serialization and deserialization.
  * XmlDictionaryReaderQuotas - Contains configurable quota values for XmlDictionaryReaders.
  * XmlDictionaryString - Represents an entry stored in a XmlDictionary.
  * XmlDictionaryWriter - Represents an abstract class that Windows Communication Foundation (WCF) derives from XmlWriter to do serialization and deserialization.
  * XmlDocument - Represents an XML document. You can use this class to load, validate, edit, add, and position XML in a document.
  * XmlDocumentFragment - Represents a lightweight object that is useful for tree insert operations.
  * XmlDocumentType - Represents the document type declaration.
  * XmlElement - Represents an element.
  * XmlEntity - Represents an entity declaration, such as <!ENTITY... >.
  * XmlEntityReference - Represents an entity reference node.
  * XmlImplementation - Defines the context for a set of XmlDocument objects.
  * XmlLinkedNode - Gets the node immediately preceding or following this node.
  * XmlNamedNodeMap - Represents a collection of nodes that can be accessed by name or index.
  * XmlNamespaceManager - Resolves, adds, and removes namespaces to a collection and provides scope management for these namespaces.
  * XmlNameTable - Table of atomized string objects.
  * XmlNode - Represents a single node in the XML document.
  * XmlNodeChangedEventArgs - Provides data for the NodeChanged, NodeChanging, NodeInserted, NodeInserting, NodeRemoved and NodeRemoving events.
  * XmlNodeList - Represents an ordered collection of nodes.
  * XmlNodeReader - Represents a reader that provides fast, non-cached forward only access to XML data in an XmlNode.
  * XmlNotation - Represents a notation declaration, such as <!NOTATION... >.
  * XmlParserContext - Provides all the context information required by the XmlReader to parse an XML fragment.
  * XmlProcessingInstruction - Represents a processing instruction, which XML defines to keep processor-specific information in the text of the document.
  * XmlQualifiedName - Represents an XML qualified name.
  * XmlReader - Represents a reader that provides fast, noncached, forward-only access to XML data.
  * XmlReaderSettings - Specifies a set of features to support on the XmlReader object created by the Create method.
  * XmlResolver - Resolves external XML resources named by a Uniform Resource Identifier (URI).
  * XmlSecureResolver - Helps to secure another implementation of XmlResolver by wrapping the XmlResolver object and restricting the resources that the underlying XmlResolver has access to.
  * XmlSignificantWhitespace - Represents white space between markup in a mixed content node or white space within an xml:space= 'preserve' scope. This is also referred to as significant white space.
  * XmlText - Represents the text content of an element or attribute.
  * XmlTextReader - Represents a reader that provides fast, non-cached, forward-only access to XML data. Starting with the .NET Framework 2.0, we recommend that you use the XmlReader class instead.
  * XmlTextWriter - Represents a writer that provides a fast, non-cached, forward-only way of generating streams or files containing XML data that conforms to the W3C Extensible Markup Language (XML) 1.0 and the Namespaces in XML recommendations. Starting with the .NET Framework 2.0, we recommend that you use the XmlWriter class instead.
  * XmlUrlResolver - Resolves external XML resources named by a Uniform Resource Identifier (URI).
  * XmlValidatingReader - Represents a reader that provides document type definition (DTD), XML-Data Reduced (XDR) schema, and XML Schema definition language (XSD) validation. This class is obsolete. Starting with the .NET Framework 2.0, we recommend that you use the XmlReaderSettings class and the Create method to create a validating XML reader.
  * XmlWhitespace - Represents white space in element content.
  * XmlWriter - Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.
  * XmlWriterSettings - Specifies a set of features to support on the XmlWriter object created by the Create method.
* Exception Classes:
  * XmlException - Returns detailed information about the last exception.
* Interfaces:
  * IApplicationResourceStreamResolver - Represents an application resource stream resolver.
  * IFragmentCapableXmlDictionaryWriter - Contains properties and methods that when implemented by a XmlDictionaryWriter, allows processing of XML fragments.
  * IHasXmlNode - Enables a class to return an XmlNode from the current context or position.
  * IStreamProvider - Represents an interface that can be implemented by classes providing streams.
  * IXmlBinaryReaderInitializer - Provides methods for reinitializing a binary reader to read a new document.
  * IXmlBinaryWriterInitializer - Specifies implementation requirements for XML binary writers that derive from this interface.
  * IXmlDictionary - An interface that defines the contract that an Xml dictionary must implement to be used by XmlDictionaryReader and XmlDictionaryWriter implementations.
  * IXmlLineInfo - Provides an interface to enable a class to return line and position information.
  * IXmlNamespaceResolver - Provides read-only access to a set of prefix and namespace mappings.
  * IXmlTextReaderInitializer - Specifies implementation requirements for XML text readers that derive from this interface.
  * IXmlTextWriterInitializer - Specifies implementation requirements for XML text writers that derive from this interface.
* Enums:
  * ConformanceLevel - Specifies the amount of input or output checking that XmlReader and XmlWriter objects perform.
  * DtdProcessing - Specifies the options for processing DTDs. The DtdProcessing enumeration is used by the XmlReaderSettings class.
  * EntityHandling - Specifies how the XmlTextReader or XmlValidatingReader handle entities.
  * Formatting - Specifies formatting options for the XmlTextWriter.
  * NamespaceHandling - Specifies whether to remove duplicate namespace declarations in the XmlWriter.
  * NewLineHandling - Specifies how to handle line breaks.
  * ReadState - Specifies the state of the reader.
  * ValidationType - Specifies the type of validation to perform.
  * WhitespaceHandling - Specifies how white space is handled.
  * WriteState - Specifies the state of the XmlWriter.
  * XmlDateTimeSerializationMode - Specifies how to treat the time value when converting between string and DateTime.
  * XmlDictionaryReaderQuotaTypes - Enumerates the configurable quota values for XmlDictionaryReaders.
  * XmlNamespaceScope - Defines the namespace scope.
  * XmlNodeChangedAction - Specifies the type of node change.
  * XmlNodeOrder - Describes the document order of a node compared to a second node.
  * XmlNodeType - Specifies the type of node.
  * XmlOutputMethod - Specifies the method used to serialize the XmlWriter output.
  * XmlSpace - Specifies the current xml:space scope.
  * XmlTokenizedType - Represents the XML type for the string. This allows the string to be read as a particular XML type, for example a CDATA section type.
* Delegates:
  * OnXmlDictionaryReaderClose - delegate for a callback method when closing the reader.
  * XmlNodeChangedEventHandler - Represents the method that handles NodeChanged, NodeChanging, NodeInserted, NodeInserting, NodeRemoved and NodeRemoving events.
