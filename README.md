import os
import json
from telegram import Update, InlineKeyboardButton.
InlineKeyboardMarkup, ReplyKeyboardMarkup
KeyboardButton
from telegram.ext import Updater, CommandHandler.
MessageHandler, Filters, CallbackContext,
CallbackQueryHandler
# Replace these with your actual bot token, admin ID.
and channel username
BOT TOKEN ="8175899243:AAFXOM11aZOnxTNnpw2-qXUwVB-GOruRs68"
CHANNEL_USERNAME ="https://t.me/+0wx4yCbtqbZhNjM1"
ADMIN ID =6691061346
USERS FILE ='users.json
FRESH_FILE ='fresh_numbers.txt
OLD FILE ='old_numbers.txt'
OTHER_FILE ='other_country_numbers.txt
# Load users from JSON
