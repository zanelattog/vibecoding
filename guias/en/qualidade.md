[Home](../../README.en.md) · [Português](../pt/qualidade.md)

# Checking the result


A polished screen can hide a broken feature. Verification should match the purpose of the change.

## Four different states

1. **File present:** a guide or configuration exists.
2. **Installed:** the component was added to the environment.
3. **Discovered:** the client can find and access the component.
4. **Workflow tested:** a real task or representative test case worked.

Record the actual state. A fictional-data example does not prove an external integration, and a successful connection does not prove every workflow.

## What to verify

| Change | Useful evidence |
| --- | --- |
| Text and documentation | Links work, images exist and wording matches the current version. |
| Interface | Main workflow, keyboard use, screen sizes and error messages. |
| Business rule | Normal cases, boundaries and relevant failures. |
| Integration | Correct service, minimum permissions and behavior when it fails. |
| Agent configuration | Tool discovery and a completed small task. |

Use the project's own commands. Type checking, static analysis, tests and builds check different aspects. Do not remove a protection merely to get a green result.

For higher-impact changes, independent review can help. Review the change and its connected behavior. After fixes, rerun affected checks; repeating everything without a reason does not improve evidence.

## Publishing the presentation

Choose public files explicitly. Check screenshots, names, links, example data and credentials. This guide does not need the private application code used in its examples.

Use the [verification record](../../modelos/en/verificacao.md). The [original toolkit's documented limits](https://github.com/soumatheusgomes/vibe-coding-toolkit/blob/790a895304e0c08b70a5b215c9d334f1c86b816c/docs/05-toolkit-validation.md) belong to that version and are not results of this adaptation.


[Credits and source](../../CREDITS.en.md)
