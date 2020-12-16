# Spam-Filter-Navie-Bayes
In this project, we're going to study the practical side of the multinomial Naive Bayes algorithm by building a spam filter for SMS messages.

To classify messages as spam or non-spam, we saw in the previous mission that the computer:

    1-How humans classify messages.
    2-Uses that human knowledge to estimate probabilities for new messages — probabilities for spam and non-spam.
    3-Classifies a new message based on these probability values — if the probability for spam is greater, then it classifies the message as spam. Otherwise, it classifies it as non-spam (if the two probability values are equal, then we may need a human to classify the message).

So our first task is to "teach" the computer how to classify messages. To do that, we'll use the multinomial Naive Bayes algorithm along with a dataset of 5,572 SMS messages that are already classified by humans.
