from EmotionDetection.emotion_detection import emotion_detector
import unittest

class TestEmotionDetector(unittest.TestCase):

    def test_emotion_detector(self):

        a = emotion_detector("I am glad this happened")
        self.assertEqual(a['dominant_emotion'],'joy')

        b = emotion_detector("I am really mad about this")
        self.assertEqual(b['dominant_emotion'],'anger')

        c = emotion_detector("I feel disgusted just hearing about this")
        self.assertEqual(c['dominant_emotion'],'disgust')

        d = emotion_detector("I am so sad about this")
        self.assertEqual(d['dominant_emotion'],'sadness')

        e = emotion_detector("I am really afraid that this will happen")
        self.assertEqual(e['dominant_emotion'],'fear')

#Call the unit tests.
unittest.main()