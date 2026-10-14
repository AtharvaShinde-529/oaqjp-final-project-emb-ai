"""
Unit tests for the emotion_detector function.
"""
import unittest
from EmotionDetection.emotion_detection import emotion_detector

class TestEmotionDetection(unittest.TestCase):
    """Test cases for the emotion detector."""

    def test_joy(self):
        """Test that 'glad' produces joy as the dominant emotion."""
        result = emotion_detector("I am glad this happened")
        self.assertEqual(result['dominant_emotion'], 'joy')

    def test_anger(self):
        """Test that 'mad' produces anger as the dominant emotion."""
        result = emotion_detector("I am really mad about this")
        self.assertEqual(result['dominant_emotion'], 'anger')

    def test_disgust(self):
        """Test that 'disgusted' produces disgust as the dominant emotion."""
        result = emotion_detector("I feel disgusted just hearing about this")
        self.assertEqual(result['dominant_emotion'], 'disgust')

    def test_sadness(self):
        """Test that 'sad' produces sadness as the dominant emotion."""
        result = emotion_detector("I am so sad about this")
        self.assertEqual(result['dominant_emotion'], 'sadness')

    def test_fear(self):
        """Test that 'afraid' produces fear as the dominant emotion."""
        result = emotion_detector("I am really afraid that this will happen")
        self.assertEqual(result['dominant_emotion'], 'fear')

if __name__ == '__main__':
    unittest.main()
