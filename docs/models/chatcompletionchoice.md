# ChatCompletionChoice


## Fields

| Field                                                              | Type                                                               | Required                                                           | Description                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ | ------------------------------------------------------------------ |
| `index`                                                            | *int*                                                              | :heavy_check_mark:                                                 | The index of this choice in the list of choices.                   |
| `message`                                                          | [models.ChatCompletionMessage](../models/chatcompletionmessage.md) | :heavy_check_mark:                                                 | N/A                                                                |
| `finish_reason`                                                    | *OptionalNullable[str]*                                            | :heavy_minus_sign:                                                 | The reason the chat completion was finished.                       |
| `logprobs`                                                         | *Optional[Any]*                                                    | :heavy_minus_sign:                                                 | Log probability information for the choice, if applicable.         |