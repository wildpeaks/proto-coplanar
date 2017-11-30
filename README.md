# Coplanar

VRML PROTO (based on `DrawGroup`) that wraps an arbitrary set of objects in a drawgroup
meant **for rendering transparent coplanar objects in the order they're provided**,
avoiding the classic z-fighting rendering issue, (e.g. an icon that should always be rendered in front of a button).

	EXTERNPROTO Coplanar [
		exposedField  MFNode  children
	] "proto.Coplanar.wrl#Coplanar"


-------------------------------------------------------------------------------

## Property `children`

The ordered list of flat **objects to render** (from "first to render" to "last to render").

Definition:
 - Field Type: `exposedField`
 - Data Type: `MFNode`
 - Default Value: `[]`


-------------------------------------------------------------------------------

