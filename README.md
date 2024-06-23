# Redwood example ShadCn Generators

These are some example files for using ShadCN in Redwood's scaffold generator.

You will need to install the following ShadCN components into Redwood:

- Card
- Table
- Button

This example also uses a wrapper component around form inputs

````

// Add this to your web/src/components/Forms/FieldWrapper.tsx

const FieldWrapper = ({ children }: { children: React.ReactNode }) => {
  return <div className="flex flex-col space-y-2">{children}</div>
}

export default FieldWrapper


```

Copy the generators folder into your 'web/' folder in redwood.

And then you should be able to scaffold out a new page


````
