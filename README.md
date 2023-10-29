# Named_Entity_Recognition_Model
Machine learning model to extract information about name from text i.e. whether the name is of a person, organization or location
# Project Highlights
* ```def encode(self, text: str, max_length: Optional[int] = None) -> List[int]:```  in ``` class Tokenizer:``` creates a vocabulary of the dataset and converts the input texts into lists of token ids.
* ```class PositionalEncoding(nn.Module): ``` inject the position information of each token in the input sequence.
  * Includes the ```forward``` method which computes the positional encoding and adds the positional encodings to the input x
* ```class TransformerModel(nn.Module):``` includes ```nn.TransformerEncoder``` layer to perform transformer operations
* ```predict``` function which takes a trained model and a dataloader, and predicts the IOB tags for all examples in the data set
