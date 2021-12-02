# contour-enhancing-Recurrent-Block
A recurrent block that can enhance contour under noisy conditions and improve ResNet50 robustness under adversarial attack.

This recurrent block is inspired by VOneNet proposed by Dapello in 2020, which introduced biological constrain into CNNs to improve their robustness. We construceted a recurrent block simulating neuron responses and interaction in V1 based on VOneNet with ResNet50 backend,  and it can further enhance the objects edge information, increase the boundary saliency, and further improve ResNet50 robustness under adversarial attack compared with VOneNet.
This is part of the code from my thesis.

The model is based on PyTorch, trained on colab GPU.
