# Redwood example Shadcn Generators

These are some example files for using Shadcn in Redwood's scaffold generator.

This assumes you have followed these instructions to install Shadcn into your Redwood project: https://github.com/redwoodjs/redwood/pull/10459

You will need to install the following Shadcn components into Redwood:

- Card
- Table
- Button

This example also uses a wrapper component around form inputs

```

// Add this to your web/src/components/Forms/FieldWrapper.tsx

const FieldWrapper = ({ children }: { children: React.ReactNode }) => {
  return <div className="flex flex-col space-y-2">{children}</div>
}

export default FieldWrapper


```

Copy the generators folder into your 'web/' folder in redwood.

And then you should be able to scaffold out a new page
